# Stock-Price-Explorer

This is a beginner-friendly project where I explored stock price data using Python, pandas, and yfinance.  
I focused on three companies: Apple (AAPL), NVIDIA (NVDA), and Amazon (AMZN).

## What I Did
- Collected last month’s stock prices using the `yfinance` library.
- Created organized DataFrames with `pd.DataFrame()`.
- Combined the data into one table with columns: `Date`, `Ticker`, and `Close`.
- Calculated average closing prices for each stock.
- Filtered rows to find days when prices were above the average.
- Saved results to CSV files (`stocks_last_month.csv` and `stocks_summary.csv`).

## Files in This Project
- **stock_price_explorer.ipynb** → Jupyter Notebook with the full code and comments.  
- **stocks_last_month.csv** → Complete dataset of AAPL, NVDA, and AMZN daily prices.  
- **stocks_summary.csv** → Summary table with one row per stock and average close.  
- **README.md** → This file, explaining the project.

## Why I Made This
This project helped me practice the basics of pandas that I learned in class:
- Creating DataFrames
- Filtering rows
- Using `.mean()` to calculate averages
- Saving outputs with `.to_csv()`
