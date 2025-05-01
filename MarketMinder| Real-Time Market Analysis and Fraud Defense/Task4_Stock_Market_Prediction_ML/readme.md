# TASK 4: Stock Market Prediction Using Machine Learning
## Overview
The purpose of this task is to analyze and predict stock market trends using historical stock data for Google (GOOG). The goal is to develop a machine learning model that forecasts future stock prices to assist investors in making informed decisions.

## Project Details
* Data Components:
  - Historical Data: Daily closing prices from 2012–2022, fetched using the yfinance library.
  - Features: Open, close, moving averages (100-day, 200-day), and volatility trends.
* Approach:
  - Used 100-day and 200-day moving averages to identify long-term trends and potential buy/sell signals.
  - Split the dataset into 80% training and 20% testing subsets for model evaluation.
  - Preprocessed the data using MinMaxScaler for normalization.
  - Created sequential input data for 100-day windows to train the predictive model.
* Model Development:
  - Built a deep Long Short-Term Memory (LSTM) model for time-series forecasting using TensorFlow/Keras libraries.
  - Configured multi-layer architecture with dropout layers to prevent overfitting.
  - Trained the model over 50 epochs with Adam optimizer and Mean Squared Error (MSE) loss function.
 
## Key Features
* Trend Analysis:
  - 100-Day Moving Average: Highlights medium-term market fluctuations.
  - 200-Day Moving Average: Acts as a long-term indicator for stock movements.
* LSTM Model:
  - Memory-driven approach captures sequential dependencies in stock price movements.
  - Accurate predictions for the next 15 days, visualized alongside actual prices.
* Prediction and Visualization:
  - Visual comparison of predicted vs actual prices using Matplotlib, showcasing the model's precision.
  - Denormalized predictions for real-world applicability.
* Future Price Forecast:
  - Framework to predict stock prices for upcoming 10 days based on historical trends and trained sequences.

### This task demonstrates the power of deep learning techniques (LSTM) in financial forecasting, providing valuable insights into Google stock trends.

  
