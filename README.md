# Stock Price Prediction Project

## Overview

This project focuses on predicting stock prices using machine learning techniques, primarily Long Short-Term Memory (LSTM) models, and compares their performance with traditional regression-based models. The dataset includes historical stock price data for multiple companies, which is preprocessed and explored to gain insights into trends and patterns.

## Key Steps

1. **Data Preprocessing**: The dataset is cleaned, and features are engineered, including the incorporation of moving average features to capture historical trends.

2. **Model Building**: LSTM models with different architectures are built and trained on the data. Additionally, traditional regression-based models like Linear Regression and XGBoost Regressor are trained for comparison.

3. **Model Evaluation**: The performance of the models is evaluated using metrics such as Root Mean Squared Error (RMSE), Mean Squared Error (MSE), and Mean Absolute Error (MAE).

4. **Prediction and Visualization**: The best-performing LSTM model is used to make predictions on unseen test data, and the results are visualized against the actual stock prices.

5. **Conclusion**: The project concludes that LSTM models, particularly a specific architecture (LSTM2) with optimized parameters, demonstrate competitive performance in predicting stock prices compared to traditional regression-based models.

## Significance

This project provides valuable insights for investors and financial analysts by showcasing the potential of LSTM models in accurately predicting stock prices. Additionally, it serves as a practical demonstration of machine learning techniques applied to real-world financial data.

## Code and Documentation

For the full project code and documentation, please visit [the GitHub repository](link-to-github-repo).
