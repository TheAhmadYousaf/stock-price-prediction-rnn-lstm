# 📈 Stock Price Prediction using RNN, LSTM & Attention

A deep learning project for time-series forecasting of stock prices using SimpleRNN, LSTM, and a custom Attention mechanism built with TensorFlow/Keras.

---

## 🎯 Objective
- Understand sequence modeling using real stock market data
- Apply Simple RNN and LSTM for time-series prediction
- Compare model performance using RMSE and MAE
- Analyze temporal dependency learning with Attention

---

## 📂 Project Structure
```
stock-price-prediction-rnn-lstm/
│
├── Stock_Price_Prediction_RNN_LSTM.ipynb   # Main Jupyter Notebook
├── AAPL_stock_data.csv                     # Apple stock dataset
└── README.md
```

---

## 📊 Dataset
- **Source:** Apple Inc. (AAPL) — Yahoo Finance via `yfinance`
- **Range:** 2018 – 2024
- **Rows:** 1500+
- **Target:** Close Price

---

## 🔧 Tech Stack
- Python 3.10
- TensorFlow / Keras
- NumPy, Pandas
- Scikit-learn (MinMaxScaler)
- Matplotlib
- yfinance

---

## 🧠 Models Built

| Model | Description |
|-------|-------------|
| Simple RNN | Baseline recurrent model (64 units) |
| LSTM | Long Short-Term Memory (64 units) |
| LSTM + Attention | LSTM with custom Bahdanau-style Attention layer |

---

## 📉 Results

| Model | RMSE | MAE | Training Time |
|-------|------|-----|---------------|
| Simple RNN | 14.5522 | 12.1385 | 3.83s |
| LSTM | 5.7250 | 4.6083 | 6.62s |
| LSTM + Attention | 7.0784 | 5.7444 | 7.00s |

> Fill in your actual results after running the notebook.

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/Theahmadyousaf/stock-price-prediction-rnn-lstm.git
cd stock-price-prediction-rnn-lstm
```

2. Install dependencies
```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn yfinance
```

3. Launch Jupyter Notebook
```bash
jupyter notebook Stock_Price_Prediction_RNN_LSTM.ipynb
```

---

## 📌 Key Concepts Covered
- Sliding window sequences for time-series
- MinMax normalization
- Vanishing gradient problem in RNNs
- LSTM gates (forget, input, output)
- Custom Attention layer in Keras
- RMSE & MAE evaluation

---

## 👤 Author
Ahmad Yousaf  
BS Artificial Intelligence
