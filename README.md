# Project 7 - Applied Data Analytics
## Project Description
This project is used as guided introduction to several, more advanced topics in data analytics. It is an exploration of applied data analytics that incorporates logging to document the process and provide feedback.

## Project Setup
### Create Virtual Enviornment
``` shell
py -m venv .venv
py -m .\.venv\Scripts\activate
```

### Install Dependencies and Upgrade Pip
``` shell
py -m pip install jupyterlab
py -m pip install pandas
py -m pip install pyarrow
py -m pip install matplotlib
py -m pip install seaborn
py -m pip install --upgrade pip
py -m pip install -r requirements.txt
```

### Freeze Requirements
``` shell
py -m pip freeze > requirements.txt
```

### Add to .gitignore
``` shell
.venv/
.vscode/
*~
.ipynb_checkpoints/
*.ipynb_meta/
```

## Data Set Utilized
[ave_hi_nyc_jan_1895-2018](https://github.com/kcbreum/datafun-07-applied/blob/main/ave_hi_nyc_jan_1895-2018.csv)

## Dependencies Imported
``` shell
import pandas as pd
import seaborn as sns
from scipy import stats
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
import numpy as np
import matplotlib.pyplot as plt
from sklearn import metrics
from sklearn.linear_model import ElasticNet, Lasso, Ridge
from sklearn.model_selection import KFold, cross_val_score
```

## Git Add and Commit
``` shell
git add .
git commit -m "update message goes here"
git push origin main
```

## Credentials
This was a required project to be completed for the MS in Data Analytics degree at Northwest Missouri State University. Assisted instructions were given by Denise Case. Additionally AI was utilized to complete this project.
Deitel, P. (2021). *INTRO TO PYTHON FOR COMPUTER SCIENCE AND DATA SCIENCE : learning to program with ai, big data, and the cloud*, global edition. Pearson Education Limited.