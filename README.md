# Module 1 project template

This repo contains:
- TEMPLATE_README: An example of a Readme for your project 
- `dsc-mod1-project-template.ipynb`: A starter jupyter notebook
  - inside the notebook there is some text and `| guiding questions within lined sections |` that should be answered in narrative form
  - sample visualizations. Their code is in the `visualizations.py` file as a reference. 
- `__init__.py` :python helper file, tells python there are packages 
- presentation pdf:
  - The online editable version of this file can be found [here](https://docs.google.com/presentation/d/1iS5kCJVBiieuUEokWLOSjuAxlz9oX-tPV2xr0i9RYdA/edit?usp=sharing)
  - Please make a copy of the file before editing
- data folder:
  - for this project this is where you will store your data
- data_cleaning_code folder:
  - `__init__.py` :python helper file, tells python there are packages 
  - contains sample `data_cleaning.py` script to clean data and prepare it for analysis and visualization
  - This is where the messy EDA/data cleaning notebook can also live
- images_and_code folder:
  - `__init__.py` :python helper file, tells python there are packages 
  - contains sample `visualizations.py` file to create the project visuals. This is an example file only. 
  - contains images used in jupyter notebook markdown
- hidden `.gitignore` file that tells git to not track certain files and folders

***
## Student instructions

1. Through github, fork this repository to you own account (if in a group project, have only one team member do steps one through five)
2. In github, on the forked repo, click "Settings"
3. On the Setting page, the first tab is "Options". On that page there  "Repository Name" with a text field, and a button "Rename"
4. Change the name of the forked repo to a project repo name of your choosing
5. If you are part of a group project(if not, proceed to step 6):
   - Go to the "Manage Access" tab within "settings"
   - Add your project team members as collaborators
   - copy the link to clone the repository and share it with teammates 
6. Through the terminal on your local machine, `git clone` the project to your local computer
7. Move the data from the project description into the `data` folder on your local machine
8. You are now ready to start using these materials!


***
## Please note
- The code within `visualizations.py` and `data_cleaning.py` is an example of well documented code.
- The visualizations in the notebook, generated from `visualizations.py` have clear axes, titles, and appropriate number formatting. Please use as a reference.
- The `dsc-mod1-project-template.ipynb`is intented to be the _final version_ of your project. 
     - The first noteook you create will not look like this. 
     - You are encouraged to start with a very disorderly notebook and clean it as you go.
- Before you finish this project, delete **this** readme from the repo using `git rm README.md`, followed by `git mv TEMPLATE_README.md README.md`