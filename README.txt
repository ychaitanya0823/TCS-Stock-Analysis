 📈 TCS Stock Price Analysis & Forecasting

This project analyzes and forecasts **Tata Consultancy Services (TCS)** stock prices using **Machine Learning, Deep Learning (LSTM)**, and **Time Series Forecasting (Prophet)**. It includes exploratory data analysis, feature engineering with technical indicators, and predictive modeling on real historical stock data.

---

📂 Dataset

- File: `TCS_stock_history.csv`
- Source: Provided by Unified Mentor Internship
- Columns:
  - Date, Open, High, Low, Close, Volume, Dividends, Stock Splits

---

 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) on historical TCS stock data
- Engineer financial indicators: RSI, MACD, Bollinger Bands
- Build predictive models:
  - ✅ Machine Learning: Random Forest Regressor
  - ✅ Deep Learning: LSTM Model using Keras
  - ✅ Time Series: Prophet Forecasting Model
- Visualize predictions and compare performance
- Deploy visuals (optional: Streamlit)

---

🧠 Technologies Used

| Tool/Library     | Purpose                            |
|------------------|-------------------------------------|
| Python           | Core programming language           |
| Pandas, Numpy    | Data manipulation & processing      |
| Matplotlib, Seaborn | Visualization                    |
| Scikit-learn     | Random Forest, metrics              |
| TensorFlow/Keras | LSTM Neural Network                 |
| Prophet          | Time-series forecasting             |
| yfinance         | Stock data sourcing (if applicable) |
| Streamlit (optional) | Dashboard (interactive UI)     |

---
 🔍 Exploratory Data Analysis (EDA)

- Line plot of Close Prices
- Moving Averages (30, 50, 200 days)
- Volume & Dividend trends
- Correlation heatmap
- Daily Price Change distribution

---

 ⚙️ Feature Engineering

- `Prev_Close`, `Day`, `Month`, `DayOfWeek`
- Technical Indicator:
  - RSI (Relative Strength Index)
  - MACD (Moving Average Convergence Divergence)
  - Bollinger Bands

---

 🤖 Models Implemented

1. 🎯 Random Forest Regressor
- Features: Open, High, Low, Volume, RSI, MACD, etc.
- Metrics:
  - MSE: ~124
  - R² Score**: ~0.9998

 2. 🧠 LSTM (Long Short-Term Memory)
- Input: Close prices reshaped for sequence modeling
- MAE: ~69.5  
- Output: Predicted vs Actual graph

3. 🔮 Prophet Forecasting
- 30-day forward forecast
- Trend, Weekly & Yearly seasonality components
- Visualized with confidence intervals

---

📊 Sample Visuals

- ✅ Actual vs Predicted (RF & LSTM)
- 📈 Forecast chart (Prophet)
- 📉 Price vs Volume scatter
- 📆 Moving average crossover strategy

---

 📦 Installation

```bash
pip install -r requirements.txt
