# formative-assessment-statistics-
This project involves a comprehensive Exploratory Data Analysis (EDA) and data preprocessing workflow on a dataset containing property prices in Bangalore

# House Price Prediction using Machine Learning
 Project Overview

This project focuses on predicting house prices using the Boston Housing Dataset. It applies data preprocessing, exploratory data analysis (EDA), and machine learning models to understand the factors affecting housing prices and to build accurate prediction models.

 ## Objectives
 
Analyze real-world housing data
Handle missing values and outliers
Build regression models for prediction
Compare model performance

## Dataset

Dataset Name: Boston Housing Dataset
Target Variable: medv (Median house value)
Features: Crime rate, number of rooms, tax rate, etc.

## Technologies Used

## Python 

Pandas & NumPy
Matplotlib & Seaborn
Scikit-learn

## Steps Performed

1. Data Loading
Loaded dataset using Pandas
Checked shape, info, and summary statistics

3. Data Cleaning

4. Checked for duplicates and missing values
Removed outliers using IQR method

5. Data Visualization
Boxplot used for outlier detection
Feature importance visualization

6. Feature Engineering
Split data into features (X) and target (y)
Train-test split (80% training, 20% testing)
Standardization using StandardScaler

7. Model Building
✅ Linear Regression
Trained baseline model
Evaluated using:
Mean Squared Error (MSE)
R² Score
🌲 Random Forest Regressor
Improved model performance
Compared results with Linear Regression
