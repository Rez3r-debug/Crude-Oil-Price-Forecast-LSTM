# Crude Oil Price Forecasting Using LSTM

## Overview
This project builds a multivariate Long Short-Term Memory (LSTM) neural network to forecast crude oil prices using historical price data and macroeconomic indicators.

## Features Used
- Crude oil price
- Monthly price change
- Percentage change
- Simulated inflation rate
- Simulated interest rate
- Real U.S. CPI data (FRED)
- Real Federal Funds Rate data (FRED)

## Model Architecture
- LSTM layers with dropout
- Adam optimizer
- Mean Squared Error loss
- Sliding window time-series approach

## Results
The model captures long-term price trends and produces realistic future forecasts with reduced mean-reversion bias after introducing macroeconomic signals.

## Limitations
- Macroeconomic indicators are simulated, not real-time
- External geopolitical events are not modeled
- Long-horizon forecasts have increasing uncertainty
- Macroeconomic indicators are lagging indicators
- Model does not incorporate geopolitical shocks or supply disruptions

## Tools & Libraries
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Author
Kachi Anugwom
