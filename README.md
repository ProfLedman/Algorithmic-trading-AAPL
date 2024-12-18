# Stock Price Prediction: Logistic Regression, CNN, and LSTM Models

This project analyzes and predicts Apple Inc. (AAPL) stock prices using three models: Logistic Regression, Convolutional Neural Networks (CNN), and Long Short-Term Memory Networks (LSTM). The goal is to compare the models' performance in forecasting stock price movements and closing prices.

## Key Features of the Analysis:
### Data Preprocessing:

Historical AAPL stock data (2010–2023) is sourced from Yahoo Finance.
Logarithmic returns and lagged features are engineered for Logistic Regression.
Time-series sliding windows are created for CNN and LSTM models.

### Models:

Logistic Regression: Predicts binary stock price direction (up or down).
CNN: Extracts short-term patterns from sequences for price forecasting.
LSTM: Captures long-term dependencies and temporal trends in stock prices.
Evaluation Metrics:

Classification metrics (accuracy, precision, recall) for Logistic Regression.
Regression metrics (MSE, MAE) for CNN and LSTM models.
Visualization of predicted vs. actual stock prices for performance comparison.
