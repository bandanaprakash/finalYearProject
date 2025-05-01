# TASK 2: STOCK PREDICTION
## Overview
The aim of this task is to predict the stock price of Google using Long Short-Term Memory (LSTM) networks. By analyzing historical stock data, the project provides insights into future trends, enabling smarter investment decisions.

## Project Details
* Data Components:
  - Google Stock Price Data: Historical closing prices, spanning over a decade from 2012 to 2022.
  - Feature Selection: Focused on key attributes such as date, open, and close prices.
* Approach:
  - Data preprocessing includes normalization, missing value handling, and splitting into training (80%) and testing (20%) datasets.
  - Created sequences of 100-day historical data to train the LSTM model.
  - Deployed deep learning using Python libraries like TensorFlow and Keras.
* Insights Extraction:
  - Built and trained a multi-layered LSTM model with dropout layers for regularization.
  - Optimized using the Adam optimizer and trained over 50 epochs.
    
## Key Features
* 100-Day Moving Average:
   - Added to visualize long-term trends and compare with actual closing prices.
   - Provides clear indicators for buy/sell actions.

* Model Performance:
   - The LSTM model effectively forecasts Google stock trends for 15 upcoming days.
   - Predictions were compared against actual values to validate accuracy.

* Visualization:
   - Plotted predicted vs actual stock prices using Matplotlib for clear visual comparison.
   - Highlighted trends and volatility in Google’s stock movement.

* Future Stock Price Prediction:
   - Created a framework to forecast prices for the next 10 days, leveraging sequential data input.

### This module demonstrates the strength of LSTM networks in capturing time-series patterns, making it a powerful tool for financial analysis.

  
