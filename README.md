# Crypto-Market-Analysis-using-CoinDCX-API
Cryptocurrency Market Analysis using CoinDCX API, Python, Pandas and Matplotlib

# 🚀 Crypto Market Analysis using CoinDCX API

## Project Overview

This project uses the CoinDCX Public API to collect real-time cryptocurrency market data and perform data analysis using Python.

The project fetches live cryptocurrency prices, stores historical data in CSV format, validates data quality, and generates visualizations using Pandas and Matplotlib.

---

## Features

- API Integration with CoinDCX
- Live Crypto Price Tracking
- CSV Data Storage
- Data Validation
- Moving Average Analysis
- Multi-Coin Comparison
- Normalized Performance Analysis

---

## Technologies Used

- Python
- Requests
- Pandas
- Matplotlib
- CoinDCX Public API

---

## 📸 Project Screenshots

### Bitcoin Moving Average Analysis

This chart shows the moving average trend of Bitcoin prices collected from the CoinDCX Public API.

![Bitcoin Moving Average](moving_average.png)

---

### Cryptocurrency Price Comparison

This chart compares the prices of multiple cryptocurrencies and helps visualize their relative market values.

![Price Comparison](comparison_chart.png)

---

### Multi-Line Trend Analysis (BTC, ETH, DOGE)

This chart displays the price trends of Bitcoin (BTC), Ethereum (ETH), and Dogecoin (DOGE) over time using data collected from the CoinDCX Public API.

![Multi-Line Trend Analysis](multi_line_chart.png)


## Project Structure

```text
Crypto-Market-Analysis/
│
├── step1_api_connection.py
├── step2_btc_price.py
├── step3_live_updates.py
├── step4_market_details.py
├── step5_save_csv.py
├── step6_data_validation.py
├── step7_moving_average.py
├── step8_price_comparison.py
├── step9_normalized_chart.py
├── step10_multiline_chart.py
├── prices.csv
├── requirements.txt
└── screenshots/
