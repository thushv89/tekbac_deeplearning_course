## Creating the `conda` Environment for the TEKBAC Workshop

1. Download and install [Anaconda](https://www.anaconda.com/download/#windows)
2. Make sure conda is in the system `PATH` by trying `conda --version` in the command prompt
3. Create a conda virtual environment using `conda create -n tekbac.deeplearning python=3.5`
4. cd into the `<project directory>`
5. Install tensorflow by typing the following in the command prompt
6. If you **do not have a GPU** use: `conda install -n tekbac.deeplearning --yes --file requirements.txt`
7. If you **do have a GPU** use: `conda install -n tekbac.deeplearning --yes --file requirements_gpu.txt`

## Activating the `conda` Environment`
1. Activate the newly created environment with `activate tekbac.deeplearning`
2. If successfully activated, your prompt in the command line should show `(tekbac.deeplearning) C:\Users\X\Documents`, instead of showing the directory you are in (e.g. `C:\Users\X\Documents`)

## Validating the installed packages
1. After activating the `conda` environment, type in `python`
2. Try to import the packages 
  * `numpy` with `import numpy as np`, 
  * `pandas` with `import pandas as pd`, 
  * `tensorflow` with `import tensorflow as tf, 
  * `matplotlib` with `import matplotlib`, 
  * 'scikit-learn` with `import sklearn`, 
  * `Pillow` with `import PIL`
  * `nltk` with `import nltk`
3. Finally make sure you do not get any errors when importing the above packages as well as you can see the version of each package by typing `print(<package>.__version__)`

## Deactivating the `conda` Environment
1. Deactivate the conda environment with `deactivate`
2. If successfully deactivated your prompt in the command line should appear normally again (e.g. `C:\Users\X\Documents`)

## Installing packages not listed in the `requirements.txt`

If you need to install a custom package, enter the following command in the command prompt `conda install -n tekbac.deeplearning <package>`



Further reading on how to setup conda environments: [Here](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)