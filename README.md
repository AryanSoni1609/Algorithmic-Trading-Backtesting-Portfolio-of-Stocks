# Equity Portfolio Analysis & Backtesting

## 📌 Overview

This project implements a portfolio backtesting system to analyze the performance of equity investments using historical market data. It focuses on evaluating returns, risk metrics, and portfolio rebalancing strategies, along with benchmarking against market indices.

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* yfinance
* Matplotlib

## 🚀 Features

* Portfolio returns calculation using historical stock data
* Risk metrics including **Sharpe Ratio** and volatility
* Portfolio allocation and **monthly rebalancing strategy**
* Benchmark comparison against market index (e.g., NIFTY 50)
* Data visualization of portfolio vs benchmark performance

## 📊 Methodology

1. Fetch historical stock price data
2. Compute daily returns
3. Construct portfolio using equal/weighted allocation
4. Apply periodic rebalancing
5. Evaluate performance using risk-adjusted metrics
6. Compare results with benchmark index

## 📈 Results

The system demonstrates how portfolio rebalancing and diversification impact overall returns and risk exposure. It highlights trade-offs between risk and return in equity investments.

## 🧠 Key Learnings

* Practical understanding of portfolio construction and backtesting
* Application of financial metrics like Sharpe Ratio
* Handling time-series financial data using Pandas
* Building data-driven decision systems

## 🔮 Future Improvements

* Add advanced optimization (mean-variance, efficient frontier)
* Include transaction costs and slippage
* Expand to multi-asset portfolios
* Integrate SQL-based data storage for scalability

## ▶️ How to Run

```bash
pip install pandas numpy yfinance matplotlib
python main.py
```
