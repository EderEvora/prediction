# 📈 Stock Price Prediction using LSTM (PyTorch)

This project applies Deep Learning techniques to predict future stock prices of Apple Inc. (AAPL) based on historical market data.

---

## 📌 Project Overview

The financial market is highly dynamic and nonlinear, making stock price forecasting a challenging task.  
In this project, a Long Short-Term Memory (LSTM) neural network was implemented from scratch using PyTorch to model temporal patterns in stock price data and generate future predictions.

---

## 🛠 Technologies Used

- Python  
- PyTorch  
- yfinance  
- pandas  
- matplotlib  
- scikit-learn  

---

## 📊 Dataset

The dataset was collected from Yahoo Finance and contains historical stock prices of Apple Inc. (AAPL) from **2015 to 2025**.

Only the **Close price** was used, as it represents the final trading value of each market day and is commonly applied in financial forecasting.

---

## 🧠 Prediction Model

A recurrent neural network based on LSTM was developed with the following configuration:

- Two stacked LSTM layers  
- 64 hidden units per layer  
- Time window of 60 past days (lookback)  
- Fully connected output layer  

The model learns short and long-term temporal dependencies to forecast future prices.

---

## 📐 Evaluation Metrics

The model performance was evaluated using:

- Mean Squared Error (MSE)  
- Mean Absolute Error (MAE)  
- R² Score  

---

## 📈 Results

The trained LSTM successfully captured historical trends and produced continuous price forecasts for the year 2026.

While exact daily prices are uncertain in financial markets, the model demonstrates strong capability in learning temporal dynamics.

---

## ▶ How to Run

1. Install dependencies:

```bash
pip install yfinance torch pandas matplotlib scikit-learn
