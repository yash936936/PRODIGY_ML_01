# PRODIGY_ML_01
# House Price Prediction Using Linear Regression

## Overview

This project demonstrates how to build a simple linear regression model to predict house prices based on property features such as square footage, number of bedrooms, and number of bathrooms. The workflow includes data exploration, preprocessing, model training, evaluation, and visualization.

## Problem Statement

Accurately predicting house prices is crucial for buyers, sellers, and real estate professionals. This project aims to develop a predictive model that estimates house prices using key features from a dataset.

## Approach

1. **Data Loading and Exploration**: Load the dataset and perform initial exploration to understand its structure and contents.
2. **Data Cleaning**: Handle missing values by imputing with column means.
3. **Feature Selection**: Use `sqft_living`, `bedrooms`, and `bathrooms` as predictors.
4. **Model Training**: Split the data into training and test sets, then train a linear regression model.
5. **Evaluation**: Assess model performance using Mean Squared Error (MSE) and R-squared (R²) metrics.
6. **Visualization**: Plot actual vs. predicted prices for visual assessment.

## How to Run

1. **Clone this repository** or download the code.
2. **Place your `data.csv` file** (with columns: `sqft_living`, `bedrooms`, `bathrooms`, `price`) in the project directory.
3. **Install dependencies**:
    ```bash
    pip install pandas numpy matplotlib scikit-learn
    ```
4. **Run the script**:
    ```bash
    python house_price_prediction.py
    ```

## Files

- `house_price_prediction.py` – Main script for data analysis and modeling.
- `data.csv` – Input dataset (not included; supply your own).

## Results

- **Mean Squared Error (MSE)** and **R-squared (R²)** scores are printed after model evaluation.
- A scatter plot shows the relationship between actual and predicted prices.

## Conclusion

This project provides a baseline model for house price prediction using linear regression. While the model captures some underlying trends, further improvements can be made by adding more features, engineering new variables, or trying advanced modeling techniques.

## Next Steps

- Add more features (e.g., location, year built).
- Experiment with other regression algorithms.
- Perform cross-validation for more robust evaluation.
- Analyze and handle outliers.
