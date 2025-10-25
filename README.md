Perfect 👍 understood — you want **short, professional, and clean README files**, with only the **necessary information** (no long paragraphs).

I’ll simplify the format while keeping the modern GitHub look with badges and icons.
Here’s the concise version for your **first repo — All Stocks 5-Year** 👇

---

### 🏦 README: All Stocks 5-Year (Short Version)

```markdown
# 🏦 All Stocks 5-Year — Stock Price Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge)
![LSTM](https://img.shields.io/badge/Model-LSTM-orange?style=for-the-badge)
![Finance](https://img.shields.io/badge/Domain-Finance-green?style=for-the-badge)

## 📘 Overview
LSTM-based model for **next-day stock price prediction** using a 5-year multi-stock OHLCV dataset.  
Focuses on forecasting the next-day closing price with **walk-forward validation** and **leakage-safe processing**.

---

## 📊 Dataset
**Name:** All Stocks 5-Year  
**Attributes:** Date, Open, High, Low, Close, Volume, Ticker  
**Goal:** Predict next-day Close for each stock.  

📁 *Path:* `Datasets/Main 1.csv`

---

## 🧠 Model
```

LSTM(128) → Dropout(0.3) → LSTM(64) → Dense(1)

````
**Metrics:** RMSE, MAE, MAPE  
**Baselines:** Naive, ARIMA, Random Forest  

---

## 🚀 Run the Project
```bash
git clone https://github.com/pranaychowdary765/-All-Stocks-5-Year-.git
cd All-Stocks-5-Year
pip install -r requirements.txt
python main.py
````

---

## 📈 Result Summary

LSTM outperformed traditional baselines, giving **lower RMSE and smoother predictions** on liquid stocks.

---

## 🔮 Future Work

* Add attention for volatility handling
* Extend to multi-asset forecasting

---

© 2025 Polepalli Pranay Chowdary

```

---

Would you like me to make **the other 3 README files (Crude Oil, Gold, NSE Tata Global)** in **this short, same style**?
```

