# 🛒 Sales Forecasting

This project performs time series forecasting on retail sales data using two powerful methods: ARIMA and LSTM.

---

## Dataset

- Monthly shampoo sales dataset (from [jbrownlee/Datasets](https://github.com/jbrownlee/Datasets))

---

## Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Statsmodels (ARIMA)
- TensorFlow / Keras (LSTM deep learning)
- Scikit-learn (data preprocessing)

---

## Workflow

1. Load and visualize monthly sales data  
2. Build an ARIMA model and forecast 12 months ahead  
3. Prepare data for LSTM and normalize it  
4. Train an LSTM model on time windows of sales data  
5. Evaluate using RMSE  
6. Visualize original vs predicted sales  

---

## Results

- ARIMA provides a classical statistical approach to forecasting.  
- LSTM models capture nonlinear temporal patterns and improve accuracy.

---

## How to Run

Copy the code into Google Colab and run step-by-step. All required libraries are pre-installed on Colab.

---

## ⭐ Star the project if you find it helpful!
