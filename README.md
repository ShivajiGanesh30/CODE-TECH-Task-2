Name : P. Shivaji Ganesh
company : CODETECH IT SOLUTIONS
ID :  CT08DS8582
Domain : Data Analysis
Duration : September to october 2024


Install and Load Libraries: We install and load necessary libraries for data retrieval (quantmod), forecasting (forecast), statistical tests (tseries), visualization (ggplot2), and LSTM modeling (keras).

Load Stock Data: We retrieve historical stock data for Apple (AAPL) from Yahoo Finance.

Data Preprocessing: We extract the adjusted closing prices and remove any missing values.

Data Visualization: We plot the stock prices to visualize trends over time.

ARIMA Model:

Check Stationarity: We use the ADF test to assess if the series is stationary.
Fit Model: We apply auto.arima() to find the best-fitting ARIMA model.
Forecast: We forecast the next 30 days and plot the forecasted values.
LSTM Model:

Prepare Data: We scale and create lagged sequences for LSTM input.
Build Model: We construct an LSTM model and train it on the training data.
Make Predictions: We use the trained model to predict stock prices.
Evaluate Models: We calculate RMSE for both ARIMA and LSTM models to compare their performance.
