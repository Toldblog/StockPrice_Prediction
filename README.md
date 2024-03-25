# Stock Price Prediction Project

## Overview

This project focuses on predicting stock prices using machine learning techniques, primarily Long Short-Term Memory (LSTM) models, and compares their performance with traditional regression-based models. The dataset includes historical stock price data for multiple companies, which is preprocessed and explored to gain insights into trends and patterns.

## Methodology
### Data Collection and Preprocessing
- We collected historical stock price data for multiple companies from the provided datasets.
- Data preprocessing steps included renaming columns, converting date formats, dropping unnecessary columns (e.g., 'open_interest'), handling missing values, and scaling features.

### Exploratory Data Analysis (EDA)
- We visualized the closing prices of each company to gain insights into historical trends and patterns.

### Feature Engineering
- We created additional features, such as moving averages, to provide context and capture underlying patterns in the data.

### Model Building
#### LSTM Models
- We constructed two LSTM architectures: LSTM1 and LSTM2, with different configurations of LSTM layers and batch sizes.
- Hyperparameters such as learning rate, batch size, and number of epochs were fine-tuned to optimize model performance.
- The models were trained using the Adam optimizer and evaluated using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).

#### Traditional Regression Models
- We also trained traditional regression-based models, including Linear Regression and XGBoost Regressor, for comparison with LSTM models.
- These models were trained using the same dataset and evaluated using the same metrics.

### Model Evaluation
- We evaluated the performance of each model using metrics such as RMSE, MSE, and MAE on both training and validation sets.
- The models were also tested on unseen data (testing set) to assess their generalization ability.

### Results and Analysis
- LSTM models demonstrated competitive performance compared to traditional regression-based models.
- LSTM2, with a time_series_steps of 30, batch_size of 128, and 10 epochs, showed the best performance in terms of prediction accuracy.
- The LSTM models outperformed Linear Regression and XGBoost Regressor in terms of RMSE, MSE, and MAE metrics.
- Visualization of predicted vs. actual stock prices showed that LSTM models accurately captured the underlying patterns in the data.

## Conclusion
- LSTM models offer a promising approach for stock price prediction, leveraging their ability to capture long-term dependencies in sequential data.
- Fine-tuning hyperparameters such as batch size and number of epochs is crucial for optimizing LSTM model performance.
- While traditional regression-based models can also provide reasonable predictions, LSTM models tend to offer better accuracy, especially for time-series forecasting tasks.

## Future Work
- Further experimentation with different LSTM architectures and hyperparameters could potentially improve model performance.
- Ensemble methods, such as combining LSTM models with traditional regression models, could be explored to leverage the strengths of both approaches.
- Integration of additional data sources, such as external market indicators or news sentiment analysis, may enhance the predictive capabilities of the models.


## Code and Documentation

For the full project code and documentation, please visit [the GitHub repository](https://github.com/Toldblog/StockPrice_Prediction).
