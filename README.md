# covid-immunity-prediction
COVID-19 immunity prediction using RNN and LSTM

---
Capstone Project

This project presents a deep learning–based approach to predict immunity levels related to COVID-19 using time-series forecasting. It leverages Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models, enhanced with optimization techniques, to analyze pandemic trends and support public health decision-making.

# Objectives

Predict COVID-19 trends to infer population immunity levels

Implement LSTM-based time series forecasting

Analyze COVID-19 data for India, USA, UK, and Chile

Compare predicted trends with real-world case and death data

Demonstrate the effectiveness of deep learning in epidemiological modeling

---

# Methodology

Data Preprocessing

Handling missing values

Scaling using MinMaxScaler

Time-series windowing (50-day sequences)

Deep Learning Models

Recurrent Neural Network (RNN)

Long Short-Term Memory (LSTM)

Model Optimization

Dropout layers to prevent overfitting

Adam optimizer with Mean Squared Error (MSE) loss

Trend Analysis

7-day moving averages

Comparative visualization of actual vs predicted cases

---

# Dataset Description

The project uses publicly available COVID-19 datasets:

India_covid_data.csv

Historical COVID-19 cases, deaths, and health indicators

India_latest_case.csv

Latest reported COVID-19 data

Global COVID-19 Dataset

Country-wise data for the US, UK, and Chile

Key Features:

Total cases

New cases

Deaths

New deaths

Smoking rates (male & female)

Life expectancy

Development indicators

---

# Model Architecture (LSTM)
Layer	Description
LSTM (3 layers)	Captures temporal dependencies
Dropout	Prevents overfitting
Dense	Final output layer

Total Parameters: 4,211

Input Window: 50 days

Output: Next-day case prediction

---

# Results & Analysis

Accurate forecasting of COVID-19 case trends

Clear visualization of:

Rising and falling infection waves

Differences between new cases and deaths

Comparative analysis across India, USA, UK, and Chile

Results support the estimation of herd immunity trends when combined with vaccination data

Performance Highlights:

Precision: 90.42%

Sensitivity: 89.53%

Specificity: 90.86%

F1-Score: 86.03%

False Positive Rate: 9.14%

---

# Technologies Used

Programming Language: Python

Libraries & Frameworks:

NumPy

Pandas

Matplotlib

Scikit-learn

TensorFlow / Keras

Environment: Jupyter Notebook
