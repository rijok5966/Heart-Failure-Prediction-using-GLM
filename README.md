# Heart Failure Prediction: A Generalized Linear Modelling Approach

## Overview
This project analyzes the risk factors contributing to heart failure and predicts the likelihood of heart failure in patients using Generalized Linear Models (GLM) with various link functions. The analysis includes exploratory data analysis, feature selection, and predictive modeling, providing valuable insights to aid healthcare professionals in early diagnosis and intervention.

## Data Description
  - Dataset: Includes 6,611 observations and 51 variables, derived from an original dataset of over 15,000 observations.
  - Features: Age, alcohol consumption, urea levels, and various heart conditions (e.g., heart failure with reduced ejection fraction).
  - Response Variable: Binary outcome indicating the presence or absence of heart failure.

## Key Highlights
- Comprehensive Analysis: Investigates significant predictors of heart failure, including age, urea levels, alcohol consumption, and specific heart conditions.
- Predictive Modeling and Feature Selection: Identified critical features using forward and backward stepwise logistic regression. Logistic regression with the logit link function achieved the best performance, with a predictive accuracy of 99.77%. The Area Under the Receiver Operating Characteristic Curve (AUC-ROC) demonstrated near-perfect performance with 99.90%.
- Real-World Impact: Helps identify patients at high risk of heart failure, supporting timely medical interventions.

## Repository Contents
- Dataset: "DataClean-fullage.csv" file consists of the data used for the analysis.
- Report: Comprehensive PDF detailing the analysis, methods, and findings.
- Code: RMD file consists of the code used for data preprocessing, logistic regression, and performance evaluation.

## Acknowledgments
- Data Source: Kaggle.
- Original Dataset: Hero DMC Heart Institute.
