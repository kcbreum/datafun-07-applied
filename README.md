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