# heart-disease-data-cleaning
Python project for exploring and cleaning the UCI Cleveland Heart Disease dataset.
# Heart Disease Data Cleaning Project

## Overview
This project explores and cleans the UCI Cleveland Heart Disease dataset using Python.

## Dataset
- **Source:** UCI Machine Learning Repository
- **Records:** 303
- **Columns:** 14

## Tools Used
- Python 3
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning
- Identified six missing values: four in `ca` and two in `thal`.
- Filled missing values using the mode of each column.
- Checked for duplicate rows and invalid categorical values.
- Used the IQR method to identify potential outliers.
- Retained potential outliers rather than deleting them automatically.

## Results
- Final dataset: 303 rows × 14 columns
- Missing values remaining: 0
- Duplicate rows: 0
- Invalid values in checked categorical columns: 0

## Project Files
- `Heart_Disease_Data_Cleaning.ipynb`: analysis notebook
- `heart_disease_cleaned.csv`: cleaned dataset
- `Heart_Disease_Data_Cleaning_Report.docx`: project report

## Dataset Source
https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/processed.cleveland.data

## Note
This is an educational data-cleaning project and is not intended for clinical diagnosis.
