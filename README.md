# AirPassengers LSTM Forecast

This project implements a Long Short-Term Memory (LSTM) neural network for time series forecasting using the AirPassengers dataset. The goal is to predict monthly totals of international airline passengers based on historical data.

## Dataset

- **Name**: AirPassengers
- **Description**: Monthly totals of international airline passengers from 1949 to 1960
- **File**: `AirPassengers.csv`

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- TensorFlow / Keras

## Model Summary

- Model Type: LSTM (Long Short-Term Memory) neural network
- Architecture:
  - Two LSTM layers with 50 units each
  - Dense output layer
- Time Steps: 10 (sliding window approach)
- Optimizer: Adam
- Loss Function: Mean Squared Error (MSE)

## How to Run

1. Clone the repository or download the files.
2. Install the required libraries:
