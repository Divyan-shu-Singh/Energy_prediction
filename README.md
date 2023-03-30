# Energy Consumption Forecasting using ARIMA
## Overview
This project aims to forecast energy consumption using the Autoregressive Integrated Moving Average (ARIMA) model. The dataset used for this project contains hourly energy consumption data, temperature, and humidity readings for a single building.

## Dataset
The dataset used in this project contains hourly energy consumption data, temperature, and humidity readings for a single building. The dataset is available in the excel format and has the following columns:

Date
Time
Temperature (°C)
Humidity (%)
Energy Consumption (kWh)
Approach
The following steps were followed to forecast energy consumption using the ARIMA model:

1. Importing the required libraries and loading the dataset into a pandas dataframe.
2. Performing exploratory data analysis (EDA) and visualizing the data using line plots, histograms, and box plots to understand the data's distribution, patterns, and outliers.
3. Performing feature engineering by creating new features, such as the time of day, day of the week, and month, to capture the patterns and trends in the data.
4. Splitting the data into training and testing sets and fitting the ARIMA model on the training data.
5. Checking the accuracy using RMSE, MSE etc.
