# LSTM-Long-Short-Term-Memory-Networks-
# Google Stock Price Prediction using LSTM

This project implements a Deep Learning model using **Long Short-Term Memory (LSTM)** networks to predict the future stock price of Google based on historical trends.

## 🚀 Overview
Predicting stock prices is a complex time-series task. This model uses a stacked LSTM architecture with Dropout regularization to capture long-term dependencies in financial data.

## 🛠️ Tech Stack
- **Python**
- **Keras/TensorFlow**
- **Pandas & Numpy**
- **Scikit-Learn** (MinMaxScaler)

## 📊 Key Features
- **Windowed Processing**: Uses a 60-day sliding window for prediction.
- **Deep Architecture**: 4 Stacked LSTM layers with 50 neurons each.
- **Overfitting Prevention**: 20% Dropout layers integrated after each LSTM block.
- **Feature Scaling**: Normalized data for faster convergence.

## 📈 Results
The model achieved an RMSE of approximately 0.0309 on the training set, indicating a strong fit to the historical patterns.
