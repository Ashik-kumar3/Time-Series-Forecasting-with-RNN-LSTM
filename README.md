# Monthly Milk Production Forecasting using LSTM

## Overview

This project implements a Long Short-Term Memory (LSTM) network, a type of Recurrent Neural Network (RNN), to forecast future monthly milk production based on historical production data.

The model learns temporal patterns from past observations and predicts future production values using time series forecasting techniques.

---

## Problem Statement

Accurate forecasting of milk production is important for supply chain planning, inventory management, and agricultural decision-making.

This project aims to predict future monthly milk production using Deep Learning-based time series forecasting.

---

## Dataset

The dataset contains historical monthly milk production records.

Features:

* Date
* Milk Production

The data is split into:

* Training Set
* Testing Set

---

## Project Workflow

1. Data Loading
2. Data Preprocessing
3. Data Normalization using MinMaxScaler
4. Time Series Sequence Generation
5. LSTM Model Development
6. Model Training
7. Prediction Generation
8. Model Evaluation

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## Model Architecture

* LSTM Layer (100 Units)
* Dense Output Layer

Training Configuration:

* Optimizer: Adam
* Loss Function: Mean Squared Error (MSE)
* Epochs: 50

---

## Features

* Time Series Forecasting
* Sequential Data Modeling
* LSTM-based Prediction
* Deep Learning for Forecasting
* Future Production Estimation

---

## Evaluation

The model performance is evaluated using:

* R² Score
* Forecast vs Actual Comparison

---

## Future Improvements

* Multi-step Forecasting
* Hyperparameter Optimization
* GRU-based Forecasting
* Advanced LSTM Architectures
* Interactive Streamlit Dashboard

---

## Skills Demonstrated

* Deep Learning
* Recurrent Neural Networks (RNN)
* Long Short-Term Memory (LSTM)
* Time Series Forecasting
* Data Preprocessing
* Model Evaluation
* TensorFlow & Keras

