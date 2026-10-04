# Week 1 Data Preparation & Exploratory Data Analysis

## Project Overview

This project demonstrates the data preparation and exploratory data analysis (EDA) process using Python and the Titanic passenger dataset.

The main objectives are:

- Data acquisition
- Data inspection
- Data cleaning
- Missing-value handling
- Duplicate checking
- Data type correction
- Feature engineering
- Exploratory data analysis
- Data visualization
- Insight generation

## Dataset

The dataset used is the Titanic passenger dataset from Kaggle.

Dataset source:
https://www.kaggle.com/competitions/titanic/data

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Data Cleaning

The following preprocessing steps were performed:

1. Checked the dataset structure and data types.
2. Checked for duplicate records.
3. Handled missing Age values using group-wise median imputation.
4. Handled missing Embarked values using the mode.
5. Removed the Cabin column because of its high percentage of missing values.
6. Created FamilySize and IsAlone features.
7. Verified the cleaned dataset.

## Exploratory Data Analysis

The analysis includes:

- Missing-value analysis
- Passenger age distribution
- Survival rate by gender
- Survival rate by passenger class
- Correlation analysis

## Key Insights

- The overall survival rate was approximately 38.4%.
- Female passengers had a considerably higher survival rate than male passengers.
- First-class passengers had a higher survival rate than second- and third-class passengers.
- Cabin had a large amount of missing data.
- Age missing values were handled using group-wise median imputation.

## Project Report

The complete documentation, methodology, Python code snippets, visualizations, and analysis are available in:

`Week_1_Data_Preparation_EDA_Titanic_Report.docx`

## Future Scope

Further analysis could include:

- Survival prediction using machine learning
- Logistic regression
- Decision tree classification
- Feature engineering using passenger titles
- Family-size analysis
- Model evaluation and cross-validation
