# Stock Price Prediction and Analysis

This project focuses on predicting and analyzing stock prices using machine learning models and time series forecasting techniques. The project is centered around the stock data of **Apple Inc. (AAPL)** retrieved using the Yahoo Finance API (`yfinance`).

## Table of Contents
1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Models Used](#models-used)
7. [Results](#results)
8. [Future Work](#future-work)
9. [License](#license)

---

## Project Overview
This project demonstrates:
- Data retrieval using Yahoo Finance.
- Exploratory data analysis (EDA) on historical stock data.
- Machine learning models to predict stock prices.
- Statistical models like ARIMA for time series forecasting.
- Evaluation of model performance using metrics such as MSE and R².

---

## Key Features
- **Data Visualization**:
  - Stock prices with moving averages (SMA & EMA).
  - Predicted vs actual prices using scatter and line plots.
- **Machine Learning Models**:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - AdaBoost Regressor
- **Statistical Analysis**:
  - Time series cross-validation using `TimeSeriesSplit`.
  - Forecasting with ARIMA.
- **Hyperparameter Tuning**:
  - GridSearchCV for Random Forest.

---

## Installation
1. upload .py files on google colab

## Models Used

- Linear Regression: Predicts Close price using Open, High, Low, and Volume.
- Random Forest Regressor: Handles missing values and feature importance. Improved prediction accuracy through hyperparameter tuning.
- ARIMA: Time series forecasting for future prices.
- AdaBoost Regressor: Combines weak predictors to improve prediction accuracy.
