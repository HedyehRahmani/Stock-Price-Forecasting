
# Stock Price Forecasting with ARIMA Model

This repository contains Python scripts for forecasting stock prices using the ARIMA model, a popular time series forecasting method. The project explores the application of ARIMA to predict future stock prices based on historical data.

## Overview

The ARIMA (AutoRegressive Integrated Moving Average) model is widely used for time series forecasting. It involves understanding and tuning three key parameters:

- **AR (p):** AutoRegression, which uses the relationship between an observation and a number of lagged observations.
- **I (d):** Integration, which involves differencing the observations to make the time series stationary.
- **MA (q):** Moving Average, which uses the dependency between an observation and a residual error from a moving average model applied to lagged observations.

This project focuses on forecasting the stock prices of a company (e.g., Apple) by tuning these ARIMA parameters to best fit the historical data and make accurate predictions.

## Project Scope

Accurate stock price forecasting is crucial for investors and financial analysts. This project applies the ARIMA model to historical stock data to predict future prices. The goal is to build a reliable forecasting model that can aid in decision-making processes.

### Role and Objective

You are tasked with developing a time series forecasting model using ARIMA to predict future stock prices. The objective is to achieve a model that provides insights into future price movements, helping investors make informed decisions.

### Key Steps

1. **Data Preprocessing:** Handling missing data, removing noise, and making the data stationary.
2. **Model Training:** Using ARIMA to train the model on historical stock prices.
3. **Evaluation:** Evaluating model performance using metrics like Mean Absolute Error (MAE) and comparing the predictions with actual stock prices.

## Getting Started

### Installation

To set up the environment, first install the required packages by running:

```bash
pip install -r requirements.txt
```

### Running the Project

Clone this repository to your local machine and navigate to the project directory:

```bash
git clone https://github.com/HedyehRahmani/Stock-Price-Forecasting.git
```

Execute the script to run the forecasting model:

```bash
python app.py
```

## Understanding the ARIMA Model

The ARIMA model is characterized by three parameters:

- **p:** The number of lag observations included in the model (AR term).
- **d:** The number of times that the raw observations are differenced (I term).
- **q:** The size of the moving average window (MA term).

## Results and Analysis

After running the model, you will receive a detailed analysis of the stock price forecasts, including plots and evaluation metrics. The results will help you understand the accuracy of the predictions and the effectiveness of the ARIMA model in forecasting stock prices.

## Contributions

Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.
