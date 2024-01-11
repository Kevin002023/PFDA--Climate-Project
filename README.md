# **PFDA--Climate-Project**
By Kevin O'Leary

This repository is my submission for the module Programming for Data Analysis as part of the Higher Diploma in Computing and Data Analytics at Atlantic Technological University.

# Contents of Repository
- This Readme file
- project.ipynb notebook which contains all of the research, analysis and plots formed.
- a .gitignore file to ignore any temporary files and folders that should not normally be committed to a repository
- Datasets Used Folder- A folder containing all of the datasets I have sourced elsewhere for analysis
- New Datasets - A folder containing any new datasets I have formed by stitching data from different sources together.

# Project Instruction

An analysis of paleo-present climate data
  - Analyse CO2 vs Temperature Anomaly from 800kyrs – present.
  - Examine one other (paleo/modern) features (e.g. CH4 or polar ice-coverage)
  - Examine Irish context:
  - Climate change signals: (see Maynooth study: The emergence of a climate change signal in long-term Irish meteorological observations - ScienceDirect)
  - Fuse and analyse data from various data sources and format fused data set as a pandas dataframe and export to csv and json formats
  - For all of the above variables, analyse the data, the trends and the relationships between them (temporal leads/lags/frequency analysis).
  - Predict global temperature anomaly over next few decades (synthesise data) and compare to published climate models if atmospheric CO2 trends continue
  - Comment on accelerated warming based on very latest features (e.g. temperature)

# How to download this repository

- Download Anaconda.
- Download VsCode or use JupyterNotebook via browser (https://jupyter.org/try).
- Clone the repository from https://github.com/Kevin002023/FODA.
- Open via VsCode or JupyterNotebooks.
- Software Used
  -  This project was done on Jupyter Notebooks using Python 3.11.15. on the editor Visual Studio Code V 1.75.1. It was used to produce both the code and this README.md file.

# The packages I used are;

'''
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_squared_error, r2_score

'''

# References
References are noted in the section in which they are used and are listed at the end of the notebook. There are some references listed which are not used directly in the notebook but which were used to gain an under