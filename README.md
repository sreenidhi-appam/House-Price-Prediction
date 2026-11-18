# House Price Prediction

## Project Overview

This project focuses on predicting house prices using Machine Learning.

A Linear Regression model is trained using housing data to predict the sale prices of houses.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- JupyterLab

## Project Workflow

1. Loaded and explored the housing dataset.
2. Checked and handled missing values.
3. Separated the data into features and target variable.
4. Split the data into training and testing sets.
5. Applied One-Hot Encoding to categorical features.
6. Trained a Linear Regression model.
7. Evaluated the model using MAE, MSE, RMSE, and R-squared.
8. Predicted house prices for the test dataset.

## Model Evaluation

The Linear Regression model was evaluated using the following metrics:

| Metric | Result |
|---|---:|
| Mean Absolute Error (MAE) | 34,122.85 |
| Mean Squared Error (MSE) | 2,918,458,029.59 |
| Root Mean Squared Error (RMSE) | 54,022.75 |
| Testing R-squared | 0.6195 |
| Training R-squared | 0.6142 |

## Prediction Output

The trained Linear Regression model was used to predict house prices for 1,459 records with missing sale prices.

The predictions were saved in a CSV file named `Predicted_House_Prices.csv`.