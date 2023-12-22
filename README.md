# Diabetes Risk Prediction Analysis

## Project Overview

This project involves a comprehensive analysis of a diabetes dataset, sourced from Kaggle, to understand the risk factors associated with diabetes and to develop a predictive model. The goal is to identify key indicators and symptoms that contribute to diabetes risk and to provide a model that can predict an individual's risk based on these factors.

## Dataset

The dataset used in this analysis includes various factors and symptoms associated with diabetes risk, such as Age, Gender, Polyuria, Polydipsia, sudden weight loss, weakness, Polyphagia, Genital thrush, visual blurring, Itching, Irritability, delayed healing, partial paresis, muscle stiffness, Alopecia, and Obesity. The target variable is the diabetes risk class (Positive/Negative).

## Analysis Steps

## Exploratory Data Analysis (EDA):

## Data Summary

- Missing Values Check
- Data Type Verification
- Initial Data Visualization
- Feature Engineering:

## Conversion of categorical variables to a numeric (binary) format for analysis
## Data Visualization:

- Age Distribution
- Symptom Frequency
- Diabetes Risk Class Distribution
- Correlation Analysis:

## Identifying the correlation between various symptoms and the diabetes risk

## Predictive Modeling:

Logistic Regression Model to predict diabetes risk
Model Evaluation including Accuracy, Precision, Recall, ROC-AUC Score
Coefficient Analysis to understand the impact of each feature

Model Interpretation and Visualization:

ROC Curve
Confusion Matrix
Coefficient Impact Visualization

## Key Findings

Symptoms like Polyuria and Polydipsia are strongly associated with increased diabetes risk.
Gender shows a significant correlation with diabetes risk, with females having a higher prevalence of risk in the dataset.
Age plays a role in diabetes risk but is not as strong a predictor as some symptoms.
The logistic regression model demonstrates good predictive performance, making it a viable tool for preliminary diabetes risk assessment.

## Usage

This analysis can be used by healthcare professionals for early identification of individuals at risk of diabetes. The insights and the predictive model can aid in targeted screening and preventive healthcare strategies.

## Technologies Used

Python for data analysis and modeling
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## How to Contribute

Contributions to the project are welcome. You can contribute in the following ways:

Suggesting improvements in the analysis
Enhancing the predictive model
Adding new visualizations or interpretation methods
