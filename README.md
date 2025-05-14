# Stock Price Prediction Using Time Series Analysis
This project focuses on predicting stock prices using historical daily closing data of multiple stocks. The dataset provides a structured view of stock price movements over time, allowing for analysis using time series forecasting techniques such as ARIMA. This is a foundational exercise in financial data analytics and forecasting.
## 📂 Dataset Overview

The dataset contains:

- **Rows**: Daily records of trading days
- **Columns**:
  - `Date`: Trading date (used as the index)
  - `Stock_1`, `Stock_2`, ..., `Stock_n`: Daily closing prices of various stocks

Each stock's price is influenced by real-world market factors such as supply and demand, company performance, and macroeconomic indicators.

---

## 🔍 Project Goals

- Load and explore historical stock data
- Analyze trends, seasonality, and stationarity
- Decompose time series components (trend, seasonality, residual)
- Apply ARIMA modeling using `pmdarima`'s `auto_arima`
- Forecast future prices for selected stocks
- Visualize historical data and future forecasts

---

## 📊 Technologies Used

| Tool/Library      | Purpose                               |
|------------------|----------------------------------------|
| Python            | Programming language                   |
| Pandas            | Data manipulation and analysis         |
| Matplotlib        | Data visualization                     |
| Statsmodels       | Time series decomposition, ARIMA       |
| Pmdarima          | Auto ARIMA modeling                    |
| Google Colab      | Development environment                |

---

## ⚙️ How to Run (Google Colab Friendly)

1. Upload the `stock_data.csv` file to your Colab session
2. Install necessary dependencies:
   ```python
   !pip uninstall -y numpy
   !pip install numpy==1.23.5
   !pip install pmdarima --no-binary :all:
