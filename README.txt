# Deep Learning for Energy Consumption Forecasting

## Project Overview
This repository contains a Jupyter notebook implementing and comparing Recurrent Neural Networks (RNN/LSTM) and Transformer models for time series forecasting of energy consumption data.

## Dataset
- Synthetic hourly energy consumption data (2000 samples)
- Features: Daily and weekly seasonality, trend, and random noise
- Univariate time series forecasting

## Models Implemented
1. **LSTM (RNN)**: 2-layer stacked LSTM with 64 hidden units
2. **Transformer**: Encoder-only architecture with positional encoding and multi-head attention

## Key Features
- Data preprocessing with MinMax scaling
- Sequence creation for time series prediction (24-hour lookback, 1-hour forecast)
- Stationarity testing (ADF test)
- Temporal train/test split (90/10)
- Comprehensive evaluation metrics: MAE, RMSE, MAPE, R²
- Model comparison and visualization

## Requirements
- Python 3.x
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Statsmodels

## How to Run
1. Open the Jupyter notebook: `RNN_energy consumption.ipynb`
2. Run all cells in order
3. The notebook will generate synthetic data, train both models, and display comparisons

## Results
Both models are evaluated on test data with performance metrics and visualizations comparing their predictions and training behavior.

## Author
B sai chatura

