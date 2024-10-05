## Overview
This project implements a machine learning model to predict the closing prices of Exchange-Traded Funds (ETFs) using historical price data. The model leverages XGBoost, a powerful gradient boosting framework, to forecast future prices based on lagged features.

## Features
Fetches historical price data from the Alpha Vantage API.
Preprocesses data to handle missing values and sort by date.
Creates lagged features for the model, allowing it to learn from previous price data.
Trains an XGBoost model to predict closing prices.
Visualizes the predictions against actual closing prices.

## Requirements
Python 3.9 or higher
pandas
requests
xgboost
scikit-learn
matplotlib

## Visualization
The script includes a visualization step that plots the actual closing prices against the predicted prices, allowing for a visual assessment of model performance.

## Example
predict S&P 500 ETF price on today (2024-10-05) 
<img width="1020" alt="Screenshot 2024-10-05 at 1 49 43 AM" src="https://github.com/user-attachments/assets/d196a09a-0d28-4c03-8bf9-f0f051ed01bc">


