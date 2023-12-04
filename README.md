[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/h_LXMCrc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12663000&assignment_repo_type=AssignmentRepo)
# DSCI 510 Final Project

## Name of the Project
“I Wish that I Could Be Like the Cool Kids”: an Analysis for Underexposed Indie Artist on Spotify

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
   
2. **Create and Activate a Virtual Environment**:

    ```
    conda create -n my_env python=3.10 -y
    ```
    this command creates a conda virtual environment called `my_env` and the Python version is `3.10`
   
    ```
    conda activate my_env
    ```


3. **Install Required Packages**:
     ```
     pip install -r final-project/requirements.txt
     ```
  

   This command installs all the packages listed in the `requirements.txt` file.


5. **Open Jupyter Notebook**:
   If Jupyter Notebook is not installed in the selected Conda environment, you can install it using:
     ```
     conda install -n my_environment jupyter
     ```
   You will have to register your conda environment with Jupyter before it can be used in the jupyter notebooks.    run the following command to register this conda environment with jupyter:
   ```
   conda install ipykernel
   python -m ipykernel install --name my_env --display-name "my_env"
   ```
   With the Conda environment activated, launch Jupyter Notebook from the terminal by typing:
   ```
   jupyter notebook
   ```

   This will open Jupyter in your default web browser. Please ensure that the Conda environment is selected in the Jupyter Notebook. Inside your Jupyter Notebook, go to Kernel -> Change Kernel and select the kernel associated with your Conda environment

   Now, you are ready to run the project within this environment.


## Instructions on how to collect data
Due to the dynamic changes in the music industry, we chose to scrape data from dynamically generated pages. To get the most up-to-date collection of songs, run `get_data.ipynb`. 

* note: it might be different from the raw data stored in `group1_raw.csv` `group2_raw.csv`, and `group3_raw.csv`.

For the following sections (Cleaning, Analysis, Visualization), please consider using files provided in the data folder in the case of inconsistent results.

## Instructions on how to clean the data, run analysis code, and create visualizations
to get consistent results as the report, please use files `group1_raw.csv` `group2_raw.csv`, and `group3_raw.csv` in the `data` folder and run `clean_analyze_visualize.ipynb`.

Each section is clearly labeled in the file.

**to clean data**:

run each cell in the `Cleaning` section.

**to run analysis code**:

run each cell in the `Analysis` section.

consider using `group1_processed.csv` and `group2_processed.csv` in the unlikely event that results show inconsistency as the report

**to create visualization**:

run each cell in the `Visualization` section. Please run the section after running `Analysis` as the visualizations are based on the analyses.
