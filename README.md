# Data_science_house_project
A simple machine learning project that predicts house prices in Melbourne using Linear Regression. It uses features like rooms, land size, distance to city, and year built. Built using Python, Pandas, and Scikit-learn.

# Melbourne House Price Prediction using Linear Regression

This project predicts housing prices in Melbourne using historical real estate data and Linear Regression.

# Overview

A simple regression project that uses features like:
-  Rooms
-  Bathrooms
-  Distance to CBD
-  Land Size
-  Building Area
-  Year Built

# Dataset

- Source: [Kaggle - Melbourne Housing Snapshot](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot)
- File: `melb_data.csv`
- Shape: ~13,000 rows × 21 columns

# Problem Statement

> Build a regression model that can predict the **Price** (in AUD) of houses in Melbourne based on key property features.

# Tech Stack

Tool          - Purpose                         

Python        - Programming Language             
Pandas, NumPy - Data Analysis                    
Matplotlib    - Visualization                    
Scikit-learn  - ML Model (Linear Regression)     


# How It Works
1. Load and clean the data
2. Select key features
3. Train/test split
4. Train Linear Regression model
5. Predict and evaluate
6. Visualize actual vs predicted prices

# Model Performance

Metric     - Value    

MSE        - 181,193,230,417.40         
RMSE       - ~425,698 AUD               
R² Score   - Around 0.6–0.7             

