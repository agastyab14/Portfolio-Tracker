# Portfolio-Tracker

A Python tool that tracks real-time NSE stock performance 
using live market data from Yahoo Finance.

## Features
- Live portfolio summary with gain/loss
- Cumulative returns vs NIFTY 50 benchmark
- Risk metrics: Volatility, Sharpe Ratio, Max Drawdown
- Rolling volatility per stock
- Stock correlation heatmap
- Monthly returns heatmap

## Dashboard
![Dashboard](dashboard.png)

## Charts
![Portfolio vs NIFTY](portfolio_vs_nifty50.png)
![Rolling Volatility](rolling_volatility.png)
![Correlation](correlation_heatmap.png)
![Monthly Returns](monthly_returns.png)

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, yFinance

## How to Run
1. pip install pandas numpy matplotlib seaborn yfinance
2. Edit the Portfolio dictionary with your own stocks
3. Run all cells in order

## Key Insights
- Portfolio showed higher volatility (~27%) vs NIFTY 50
- Sharpe Ratio of -0.93 indicates poor risk-adjusted returns
- Max Drawdown of -38.7% during the 2026 correction
- CDSL and IREDA show highest correlation (0.58)
