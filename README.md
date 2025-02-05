# Data Science Project

## Overview
This project focuses on Water Quality predicting using machine learning.

## Setup
1. Clone the repository: `git clone https://github.com/chantharith-NY/data-science-project.git`
2. Create the virtual environment (If you had it move to part 3'): `python -m venv venv`
3. Activate the venv:
- Windows: `venv\Scripts\activate`
- MacOS/Linux: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Deactivate: `deactivate`
6. You'll have all the library in your venv and you can use it as kernel in notebook.

## If you have set up already, you could pull it:
1. Fetch (gets all the change history of a tracked branch/repo.): `git fetch origin`
2. Merge (combines the current branch, with a specified branch): `git merge origin/main`

** Note **:
You should go to the repo folder and use this: 
`git pull`

## Folder Structure
- `data/`: Raw and processed data.
- `notebooks/`: Jupyter notebooks for analysis.
- `src/`: Python scripts for preprocessing and modeling.

## How to Contribute
1. Create a new branch: `git checkout -b feature-branch-name`
2. Make your changes and commit: `git commit -m "Description of changes"`
3. Push the branch: `git push origin feature-branch-name`
4. Open a pull request.

## How to update virtual environment
1. Activate the venv:
- MacOS: `source venv/bin/activate`
- Windows: `venv\Scripts\activate`
2. Install the New Packages
Install the required packages using `pip`, for example:
`pip install numpy`
3. Update `requirements.txt`
After installing the new packages, update the requirements.txt file so others can replicate the environment:
`pip freeze > requirements.txt`
4. Deactivate the Virtual Environment
Once done, deactivate the virtual environment:
`deactivate`
5. Commit and Push Changes the `requirements.txt`
Make sure to commit and push the updated `requirements.txt` file to the repository so your teammates can install the new dependencies:
- `git add requirements.txt`
- `git commit -m "Update requirements.txt with new packages"`
- `git push origin main`

## Update juperter notebook file into repo
- Update notebook file for commit:
`git add your_notebook.ipynb`
- Commit the Changes:
`git commit -m "Update Jupyter Notebook with new changes"`
- Push the Changes:
`git push origin main`

## Update python file into repo
- Update python file for commit:
`git add your_file.py`
- Commit the changes:
`git commit -m "Update Python with new changes"`
- Push the Changes:
`git push origin main`
