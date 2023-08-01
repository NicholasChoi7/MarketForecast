# Demo
https://www.loom.com/share/110bdfeed48e4c968c2d697d6f921d94?sid=6debf1dc-1642-4e11-bd60-c6f6c991d7de

# Market Forecast
Welcome to Market Forecast! This is a simple Streamlit web application that allows you to forecast stock prices for selected companies using Facebook's Prophet forecasting model and visualize the forecasted data.

# How it works
Market Forecast fetches historical stock price data using Yahoo Finance API for the given company and uses Facebook's Prophet library to make future price predictions.

You can select a company (AAPL, GOOG, MSFT, GME) from the dropdown menu and choose the number of years you want to predict using the slider.

# Features
Select from a list of popular company stocks for prediction.
Slide to select the number of years to forecast into the future.
Visualize the raw historical data along with forecasted stock prices.
Plot the individual components of the forecast (trend, weekly, and yearly seasonality).
Data Source
The historical stock price data is fetched using Yahoo Finance API (yfinance). The data ranges from "2015-01-01" to the current date.

# Forecasting Model
Market Forecast uses Facebook's Prophet forecasting model, which is designed for time-series forecasting with strong seasonality patterns and holidays.

# Note
Please note that stock market prediction models are subject to various uncertainties and should not be solely relied upon for financial decisions.
