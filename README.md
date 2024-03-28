### cintel-04-local

## Penguins Dashboard

## Project Overview
This project utilizes Python and Shiny to deploy an interactive web dashboard using the Palmer Penguins dataset.

## Project Setup
1. Create a repository on GitHub in the browser
2. Clone the repository
```
git clone https://github.com/bncodes19/cintel-04-local
```
3. Create the virtual environment in the project folder
``` shell
python3 -m venv .venv
```
4. Activate the virtual enivronment
``` shell
source .venv/bin/activate
```
5. List the required packages in a text file "requirements.txt". There should be one package per line. The requirements file should look like this:
```
faicons
palmerpenguins
pandas
pyarrow
plotly
seaborn
shiny
shinylive
shinywidgets
```
6. Install the requirements file in a terminal
``` shell
python3 -m pip install -r requirements.txt
```
7. Freeze the requirements
``` shell
python3 -m pip freeze > requirements.txt
```
8. Create a .gitignore file in the project folder using the standard Python gitignote template: [link to .gitignore for this project](https://github.com/bncodes19/cintel-04-local/blob/main/.gitignore)

10. Add, commit, and push changes to the remote repo often
```
git add .
git commit -m "commit message"
git push origin main
```
