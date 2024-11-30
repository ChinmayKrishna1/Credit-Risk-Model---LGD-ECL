# Credit Risk Modeling Project
## Overview

This project focuses on building a credit risk model to assess the likelihood of loan defaults. The project involves extensive preprocessing, feature engineering, and preparation of datasets for predictive modeling. The work includes creating categorical variables, binning numeric variables into meaningful intervals, and preparing the dataset for machine learning models.
Project Steps
1. Data Preprocessing

    Handled missing values and ensured consistency in data.
    Applied label encoding to categorical variables for compatibility with machine learning models.

2. Feature Engineering

    Employment Length (emp_length_int):
    Categorized employment length into discrete binary variables:
        <1 year, 1 year, 2-4 years, 5-6 years, 7-9 years, 10+ years.

    Months Since Issue (mths_since_issue_d):
    Binned numeric values into categories:
        <38 months, 38-39 months, 40-41 months, 42-48 months, 49-52 months, 53-64 months, 65-84 months, and >84 months.

    Interest Rate (int_rate):
    Segmented interest rates into predefined ranges:
        <9.548%, 9.548-12.025%, 12.025-15.74%, 15.74-20.281%, and >20.281%.

3. Binary Indicator Creation

    Created binary columns to indicate whether a specific value or range applies for various features (e.g., employment length, months since issue, and interest rates).

4. Data Transformation

    Used pd.cut to transform continuous variables into categorical intervals for better interpretability and model readiness.

5. Modeling Preparations

    Prepared the dataset for machine learning by engineering features and ensuring they are in a format suitable for models like logistic regression, LightGBM, and XGBoost.

How to Use

    Prerequisites:
        Python (3.x)
        Libraries: pandas, numpy

    Running the Project:
        Load the dataset into a pandas DataFrame.
        Execute the preprocessing and feature engineering scripts to prepare the data.
        Train machine learning models using the engineered features.

    Expected Outcome:
        Predict the likelihood of default for loans using the engineered features.

Future Work

    Implement machine learning models (e.g., Logistic Regression, LightGBM, XGBoost).
    Evaluate model performance using metrics such as accuracy, precision, recall, and AUC-ROC.
    Fine-tune models and experiment with additional features to improve predictive power.
