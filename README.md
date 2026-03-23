# California Housing Price Analysis

## Overview
This project analyzes the California Housing dataset to understand the key factors that influence housing prices and to build predictive models.

## Objectives
- Explore relationships between features and housing prices
- Perform data cleaning and preprocessing
- Build and compare machine learning models

## Data
The dataset contains information from the 1990 California census, including:
- Median income
- Housing characteristics (rooms, population, households)
- Location (ocean proximity)
- Median house value

## Methods
- Data cleaning (handling missing values)
- Exploratory Data Analysis (visualizations)
- Feature engineering (rooms per household)
- One-hot encoding for categorical variables
- Model building:
  - Linear Regression
  - Random Forest Regressor

## Results
- Linear Regression R²: ~0.65
- Random Forest R² (test): ~0.83

The Random Forest model performed significantly better, indicating that housing prices depend on non-linear relationships between features.

## Key Insights
- Median income is the strongest predictor of housing prices
- Houses near the ocean tend to be more expensive
- The dataset contains a price cap at $500,000, which may affect analysis

## Tools Used
- Python
- pandas
- matplotlib
- scikit-learn

## Conclusion
This project demonstrates how data preprocessing, feature engineering, and model selection impact predictive performance. More complex models like Random Forest can better capture real-world patterns compared to simple linear models.
