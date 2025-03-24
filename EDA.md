# EDA Notes from Nick

## Overall

- We have 1.7 million observations, these models are going to take a hot sec to train and evaluate
- 15 numeric, 5 text, might have to do something with those or drop them
- 2 categorical?

## Variables Notes

- can drop spotify_id
  - can we drop song name, album name and such? would those factor into the movement of the songs?
- daily rank is evenly distributed, which means we have 50 songs for every day which is GREAT
- We have a lot of variables that have a signifcant amount of 0s but the 0s are meaningful in this context, means no movement, or 0 instrumentalness, doesn't mean missing data so we are good, not bad
- drop snapshot date, gives interesting info, this data was collected over 2 years, but meta data that isn't important to the model imo
- country has a good amount of missing values, which is not justified or contextualized, so that may be worth dropping, 1.4% or roughly 24,000 values

## Correlations Notes

- Acousticness is very negatively correalted with loudness and energy which makes sense
- Energy is very postiviely correlated with loudness, also makes sense
- Tempo and time_signature are highly correlated
