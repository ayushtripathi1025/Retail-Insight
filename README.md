# BigMart Sales Prediction Model Documentation

## Overview

This project focuses on predicting BigMart sales using machine learning techniques. Three main models were employed: Linear Regression, Random Forest Regression, and a Grid Search-optimized Random Forest. The goal was to accurately predict sales based on various features like product weight, type, visibility, and store details.

## Dataset

- **Source**: Data sourced from CSV files stored in Google Drive.

## Process

### 1. Exploratory Data Analysis

- Utilized `dtale` for interactive exploration and `ydata-profiling` for detailed reports.

### 2. Model Development

- **Linear Regression**:
  - Baseline model for initial predictions.
  
- **Random Forest Regression**:
  - Used 1000 estimators for robust predictions.
  
- **Grid Search-optimized Random Forest**:
  - Tuned hyperparameters (`n_estimators`, `max_depth`, `min_samples_leaf`) for improved accuracy.

### 3. Model Evaluation

- Assessed models using metrics like `r2_score`, `mean_absolute_error`, and `root_mean_squared_error`.
- Selected the best-performing model based on evaluation results.

### 4. Outcome

- Achieved high `r2_score` and low mean squared error, indicating effective prediction capabilities.
- Saved and validated the model for future predictions using test data.
