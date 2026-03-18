# Random Forest Classification - Diabetes Prediction

## Overview
This project builds a Random Forest machine learning model to predict 
diabetes status using clinical and demographic variables from the 
National Health and Nutrition Examination Survey (NHANES).

## Methods
- **Data preparation:** cleaning, filtering and train/test split (70/30)
- **Class imbalance handling** using class weights
- **Random Forest** classification with 500 trees
- **Model evaluation:** confusion matrix, AUC-ROC curve
- **Variable importance** analysis using the `vip` package

## Key Findings
- AUC-ROC = 0.779 (good discriminative ability)
- Age was the strongest predictor of diabetes
- Total Cholesterol ranked second despite no significant univariate difference
- BMI and Race were also important predictors

## Tools & Packages
- R 4.5.3
- `randomForest`, `caret`, `pROC`, `vip`, `tidyverse`

## Files
- `random_forest_diabetes_nhanes.Rmd` — R Markdown source code
- `random_forest_diabetes_nhanes.html` — Full rendered report
