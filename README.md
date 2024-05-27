# Statistical-Analysis-of-Sport-Data
This repository contains an R script for analyzing a sports data. 

This repository contains an R script that analyzes the relationship between Lean Body Mass (LBM) and Body Mass Index (BMI) in males and females. The script performs the following steps:

Data Loading and Inspection: Loads data from an Excel file, displays the first few rows, checks the data types, summarizes the data, and checks for missing values and outliers.

Exploratory Data Analysis (EDA): Creates histograms and scatter plots to visualize the distributions of LBM and BMI and their relationship.

Statistical Tests: Conducts Anderson-Darling tests for normality and Levene's test for equality of variances. Performs a Welch's t-test to compare mean LBM between males and females.

Correlation Analysis: Calculates correlation coefficients between LBM and BMI for both males and females.

Linear Regression Modeling: Builds a linear regression model to predict LBM based on BMI for males.

Model Diagnostics: Checks the assumptions of the linear regression model using Q-Q plots and residual plots.

Hypothesis Testing: Tests the hypothesis of a linear relationship between LBM and BMI.

Predictive Performance Assessment: Evaluates the model's predictive performance using Mean Squared Error (MSE) on a separate test dataset.

The script provides a comprehensive analysis of the relationship between LBM and BMI, demonstrating the use of statistical tests and linear regression modeling in R.
