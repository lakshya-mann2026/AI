# Linear Regression

## What Is Linear Regression?

Linear Regression is a supervised Machine Learning algorithm used to predict a continuous numerical value by learning the relationship between input features and a target variable.

**For a single feature:**

`Predicted value = intercept + slope × input`

`ŷ = b₀ + b₁x`

**For multiple features:**

`ŷ = b₀ + b₁x₁ + b₂x₂ + ... + bₙxₙ`

Where:

- `ŷ` = predicted value
- `x` or `x₁, x₂, ...` = input features
- `b₀` = intercept
- `b₁, b₂, ...` = learned coefficients

## Learning Objectives

- Understand features, target variables, training data, and test data.
- Load, inspect, and visualize a real-world dataset.
- Train a Linear Regression model using scikit-learn.
- Generate predictions and evaluate model performance.
- Understand regression metrics, residuals, and model limitations.

## Prerequisites

- Basic arithmetic and familiarity with simple equations.
- No separate Python course is required. Python concepts and libraries will be introduced as needed.

## Learning Examples

### 1. House Price Prediction

A practical example of predicting house prices using a housing dataset. It introduces data exploration, preprocessing, feature selection, model training, and evaluation.

**Topics:** Pandas, NumPy, data visualization, outlier handling, multicollinearity, feature scaling, Linear Regression, and regression metrics.

[Open the House Price notebook in Google Colab](https://colab.research.google.com/)

### 2. California Housing Dataset

Build a Linear Regression model using the California Housing dataset available through scikit-learn. Explore housing features, predict median house values, and evaluate predictions on unseen data.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/AI/blob/main/01_machine_learning/01_linear_regression_california_housing.ipynb)

## General Workflow

1. Load and understand the dataset.
2. Explore features and the target variable.
3. Clean and preprocess the data where necessary.
4. Split the data into training and testing sets.
5. Train the regression model.
6. Generate predictions.
7. Evaluate results using MAE, RMSE, and R².
8. Experiment with features and interpret the results.

## Evaluation Metrics

- **MAE:** Average absolute prediction error.
- **RMSE:** Square root of the average squared prediction error.
- **R²:** Measures performance relative to a mean-prediction baseline.

## Learning Through Experiments

Change features, compare models, inspect prediction errors, and explain how the changes affect performance.

**Principle:** Run the code, experiment with it, understand the results, and build upon what you learn.
