# StockMarket-Prediction-ML-DL
## Overview
This repository contains the implementation of various Machine Learning (ML) and Deep Learning (DL) models to predict stock market closing prices. The models are applied to historical stock data from **American Airlines (AAL)** and **Delta Airlines (DAL)**, obtained using the Alpha Vantage API. The study compares the performance of different models using metrics such as **Mean Squared Error (MSE)**, **Mean Absolute Error (MAE)**, and **R² Score**.

## Models Implemented
- **Machine Learning Models:**
  - K-Nearest Neighbors (KNN)
  - Linear Regression
  - Random Forest Regressor
- **Deep Learning Models:**
  - Artificial Neural Network (ANN)
  - Recurrent Neural Network (RNN)
  - Long Short-Term Memory (LSTM)

## Dataset
- The datasets used are historical stock price data for American Airlines and Delta Airlines.
- Features: `Open`, `High`, `Low`
- Target Variable: `Close`
- Data Source: Alpha Vantage API



## Results
- **LSTM** outperformed other models with the lowest MSE and MAE scores, demonstrating its ability to capture long-term dependencies.
- **KNN** and **Random Forest** performed well on low-volatility data but struggled with high-volatility data.
- **ANN** and **RNN** provided better performance compared to traditional ML models, but LSTM excelled in both accuracy and robustness.

