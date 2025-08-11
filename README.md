# EDA_Task5
Exploratory Data Analysis project involving data cleaning, visualization, and interpretation of patterns.

This project involved performing an Exploratory Data Analysis (EDA) on the provided dataset (train_eda.csv).
The main goal was to inspect, clean, and visualize the data to identify patterns, detect anomalies, and draw meaningful insights.

**Files in this Repository**

task5_eda.ipynb — Jupyter Notebook containing all code, plots, and observations.

report_task5.pdf — PDF version of the notebook for submission.

data/train_eda.csv — Dataset used for the analysis.

figures/ — Folder containing saved plots from the analysis.

README.md — Project description and instructions.

**Tools and Libraries Used**

Python (3.x)

pandas — For data handling and manipulation

numpy — For numerical calculations

matplotlib — For creating visualizations

seaborn — For advanced statistical plots

missingno — For visualizing missing data

Jupyter Notebook — For running and documenting the analysis

**Steps Performed**

Imported the necessary libraries and set up basic plotting configurations.

Loaded the dataset from the data folder.

Inspected the dataset for structure, column types, and missing values.

Visualized missing data patterns using missingno.

Plotted the distribution of numeric features using histograms.

Plotted the counts of categorical features using countplots.

Compared numeric and categorical variables using boxplots.

Explored correlations between numeric columns using a heatmap.

Analyzed relationships between selected variables using pairplots.

Compared survival rates across categorical variables.

Added Markdown notes after each plot to document observations.

**Key Insights** 

Most passengers were between 20 and 40 years old.

Third class passengers formed the largest group.

Fare was strongly related to passenger class.

Female passengers had a higher survival rate than male passengers.

First class passengers were more likely to survive.

**How to Run This Project**

Clone this repository or download the project folder to your computer.

Open a terminal in the project directory.

Activate the virtual environment (if you are using one):


- Command Prompt:

- cmd

.venv\Scripts\activate.bat
Install the required Python libraries:

- bash

pip install notebook pandas matplotlib seaborn missingno numpy
Launch Jupyter Notebook:

- bash

jupyter notebook
- Open task5_eda.ipynb and run all the cells to reproduce the analysis.
