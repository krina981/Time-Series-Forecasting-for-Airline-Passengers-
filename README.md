# Time Series Forecasting for Airline Passengers ✈️📈

## Overview
This project focuses on time series forecasting using historical data of airline passengers. Time series forecasting is a method of predicting future values based on historical data points ordered by time. In this project, we use various techniques such as ARIMA, SARIMA, Exponential Smoothing, and LSTM to forecast future passenger numbers.

## Data
The dataset used in this project is called "AirPassengers.csv". It contains the monthly totals of international airline passengers from 1949 to 1960.

## Techniques Used
- **ARIMA (AutoRegressive Integrated Moving Average):** A classical approach for time series forecasting that models the next step in the sequence as a linear function of the observations and residual errors.
- **SARIMA (Seasonal AutoRegressive Integrated Moving Average):** An extension of ARIMA that includes seasonal components.
- **Exponential Smoothing:** A method for smoothing time series data using weighted averages.
- **LSTM (Long Short-Term Memory):** A type of recurrent neural network (RNN) architecture well-suited to sequence prediction problems.

## Files
- **airline_passenger_forecasting.ipynb:** Jupyter Notebook containing the Python code for time series forecasting.
- **AirPassengers.csv:** Dataset containing historical data of international airline passengers.
- **README.md:** This file, providing an overview of the project.

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- statsmodels
- scikit-learn
- tensorflow

## Usage
1. Make sure you have all the dependencies installed.
2. Run the `airline_passenger_forecasting.ipynb` notebook to see the time series forecasting in action.

## Results
- The notebook contains detailed results and visualizations for each forecasting method.
- Evaluation metrics such as AIC (Akaike Information Criterion) and BIC (Bayesian Information Criterion) are used to assess model performance.

## Conclusion
Time series forecasting is a valuable tool for predicting future trends based on historical data. By employing various techniques, we can make informed decisions and plan for the future, especially in fields like airline passenger traffic, where accurate forecasting is crucial.
