# Car Price Prediction – Machine Learning Project
## Project Description

This project applies machine learning techniques to predict car prices based on vehicle specifications and categorical attributes. The work follows a complete data science pipeline, including data exploration, preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation.

## Problem Statement

Accurately predicting car prices is essential for automotive businesses and consumers. This project aims to analyze key factors influencing car prices and build regression models capable of reliable predictions.

## Key Skills Demonstrated

- Exploratory Data Analysis (EDA)

- Data Cleaning and Preprocessing

- Feature Engineering and Selection

- Regression Modeling

- Hyperparameter Tuning

- Model Evaluation

- Python & Scikit-learn

## Dataset Overview

The dataset includes:

- Numerical features: engine size, horsepower, RPM, vehicle dimensions

- Categorical features: brand, fuel type, body style, engine type

- Target variable: car price

## Exploratory Data Analysis

- Identified strong correlations between price and engine-related features

- Observed negative relationship between price and fuel efficiency

- Detected realistic outliers representing premium vehicles

- Analyzed pricing variation across brands and body styles

## Data Preprocessing

- Handled missing values using median (numerical) and mode (categorical)

- Converted object-type numerical columns to numeric format

- Applied One-Hot Encoding for categorical variables

- Scaled features using StandardScaler

- Selected features based on correlation analysis

## Models Implemented

- Multilinear Regression (baseline model)

- Decision Tree Regression (with depth control)

- KNN Regression (with hyperparameter tuning)

## Model Evaluation

Models were evaluated using:

- Mean Squared Error (MSE)

- R² Score

After tuning, KNN Regression achieved the best performance, demonstrating strong generalization and predictive accuracy.

## Key Results

- Engine size, horsepower, curb weight, and brand are the most influential features

- Non-linear and distance-based models outperform linear regression

- Feature scaling significantly improves KNN performance

- Hyperparameter tuning reduces overfitting and improves accuracy

## Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

## Conclusion

This project highlights the importance of data preprocessing, feature selection, and model tuning in regression problems. The results demonstrate how machine learning can effectively model complex relationships in real-world pricing data.
