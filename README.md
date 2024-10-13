# LDA vs PCA - Diabetes Detection

## Overview
This project aims to learn more about the variables impacting the course of diabetes and create prediction models that will help with early identification and individualized treatment plans by examining and evaluating the diabetes dataset.

There are 2 analysis methods used in this project; Principal Component Analysis (PCA) and the second one is Linear Discriminant analysis (LDA). 
PCA is beneficial as it lowers the dimensionality of the dataset by converting the original features into a new collection of uncorrelated variables (principal components). This reduction reduces problems associated with the curse of dimensionality, improves the interpretability of the model, and helps control computing complexity. 
Regarding LDA, when the conditions of normality and equal covariance matrices are satisfied, it is known to operate successfully. In some situations, it can perform better than other classification methods, especially if the dataset's dimensionality isn't too large. 

## Files
- `diabetes.csv`: this dataset has 9 columns including the target variable, glucose, blood pressure, insulin, etc.
- `Project-code.Rmd`: this file contains PCA and LDA testing on the diabetes dataset using R.
- `Data Visualization Project.pdf`: this file contains a report highlighting our findings. 
