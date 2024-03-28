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
11. Build client-side app and serve the app locally
```
shiny static-assets remove
shinylive export penguins docs
```
```
python3 -m http.server --directory docs --bind localhost 8008
```
12. Open the app locally on http://localhost:8008/

13.  Publish GitHub Pages for the repository
    1. Go to the repository on GitHub and navigate to the **Settings** tab.
    2. Scroll down and click the **Pages** section down the left.
    3. Select branch main as the source for the site.
    4. Change from the root folder to the docs folder to publish from.
    5. Click Save and wait for the site to build.
    6. Eventually, be patient, your app will be published and if you scroll to the top of the Pages tab, you'll see your github.io URL for the hosted web app. Copy this to your clipboard. 
    7. Back on the main repo page, find the About section of the repo (kind of upper right).
    8. Edit the "About" section of the repository to include a link to your hosted web app by using the Pages URL. 
