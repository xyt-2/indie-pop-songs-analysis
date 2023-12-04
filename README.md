[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/h_LXMCrc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12663000&assignment_repo_type=AssignmentRepo)
# DSCI 510 Final Project

## Name of the Project
“I Wish that I Could Be Like the Cool Kids”: an Analysis of Underexposed Indie Artist on Spotify

## Team Members (Name and Student IDs)
Sydney Hu (8560984456)

Stephanie Shaw (2344808735)

## Instructions to create a conda enviornment
To run this project, you need to have Conda installed. If you don't have Conda, you can install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) (a minimal installer for Conda) or [Anaconda](https://www.anaconda.com/products/individual) (which includes Conda and other useful data science tools).

### Setting Up the Conda Environment
1. **Clone the Repository**: First, clone this repository to your local machine using:
   `git clone https://github.com/USC-DSCI-510/final-project.git`
   
2. **Create and Activate a Virtual Environment**:

- For Windows:

  ```
  python -m virtualenv venv
  .\venv\Scripts\activate
  ```

- For macOS and Linux:

  ```
  python -m virtualenv venv
  source venv/bin/activate
  ```

3. **Install Required Packages**:
   `pip install -r requirements.txt`

This command installs all the packages listed in the `requirements.txt` file.

Now, you are ready to run the project within this environment.



## Instructions on how to install the required libraries
run the following code:
pip install -r requirements.txt

## Instructions on how to collect data
run get_data.ipynb to get the most up-to-date song data. 
* note: it might be different from the raw data stored in 'group2_raw.csv'. 

## Instructions on how to clean the data
to get consistent results as the report, please use files 'group1_raw.csv' 'group2_raw.csv', and 'group3_raw.csv'.
run clean_data.ipynb


## Instrucions on how to run analysis code and create visualizations
to get consistent results as the report, please use files 'group1_processed.csv' and 'group2_processed.csv'.
run run_analysis_visualization.ipynb
