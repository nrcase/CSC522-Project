# CSC522-Project

# Installation

I used Python 3.10.6 to run this, other versions of python should work as long as they are not too old or too new. If you specfically want to use Python 3.10.6, Pyenv is a tool that can be used to switch around the python version you are using very easily. An optional step before begining the installation below is to download pyenv 3.10.6 and set that as your python version.

## Instructions

1. Download the dataset and unzip the csv and put it into the repository
   - unfortunately the dataset is too big and cannot be pushed to github :(
2. Then create a virtual python enviroment using the command `python3 -m venv venv`
   - this will create a python virtual enviroment in the repository that will be used as the kernel for the jupyter notebooks
3. Activate the virtual enviroment and the run `pip install -r requirements.txt`
   - this will install all the required libraries to run the code with the right version
4. Open one of the Jupyter Notebooks in your favorite IDE that supports Jupyter Notebooks (VSCode, etc...) and select the kernel to be the virtual enviroment you have created.
   - This can be tricky sometimes as the IDE will sometimes not recongize the venv/Jupyter kernel, it may take some playing around or googling
5. You should be able to run the notebooks!
