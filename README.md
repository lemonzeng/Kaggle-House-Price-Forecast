# House Price Prediction Project

## Project Overview
This project aims to predict house prices using the Ames Housing dataset, as part of the Kaggle "House Prices: Advanced Regression Techniques" competition. Our goal is to develop a machine learning model that accurately predicts the sale price of homes based on various features.

## Data
The dataset consists of 1460 training examples with 81 features, including both numerical and categorical variables. The target variable is the sale price of the house.

## Current Progress
We have completed the initial data exploration and exploratory data analysis (EDA). Key findings include:

1. Data overview: 1460 samples, 81 features
2. Missing value analysis: Several features have high percentages of missing values
3. Target variable (SalePrice) analysis: Right-skewed distribution
4. Feature correlation analysis: Identified top correlated features with SalePrice

## Steps
1. Data Cleaning:
   - Handle missing values
   - Address outliers

2. Feature Engineering:
   - Create new features (e.g., TotalSF, HouseAge)
   - Encode categorical variables
   - Transform skewed numerical features

3. Feature Selection:
   - Use correlation analysis and feature importance techniques

4. Model Development:
   - Implement baseline models (Linear Regression, Ridge, Lasso)
   - Experiment with advanced models (Random Forest, XGBoost)
