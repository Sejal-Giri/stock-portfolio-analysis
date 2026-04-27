# Stock Portfolio Analysis — Indian Large Cap Stocks vs Nifty 50

## Project Overview
A 2-year stock portfolio analysis of 5 Indian large-cap stocks benchmarked against the Nifty 50 index. The project calculates key financial metrics including CAGR, Sharpe Ratio, Beta, and Standard Deviation to evaluate risk-adjusted performance.

## Stocks Analysed
| Stock | Sector |
|---|---|
| Reliance Industries (RELIANCE.NS) | Energy & Retail |
| HDFC Bank (HDFCBANK.NS) | Banking |
| Infosys (INFY.NS) | Information Technology |
| Asian Paints (ASIANPAINT.NS) | Consumer Goods |
| Sun Pharma (SUNPHARMA.NS) | Pharmaceuticals |

**Benchmark:** Nifty 50 (^NSEI)

## Tools & Libraries Used
- Python
- yfinance — stock data extraction
- pandas & numpy — data manipulation and calculations
- matplotlib & seaborn — data visualisation
- Google Colab — development environment

## Key Metrics Calculated
- CAGR (Compounded Annual Growth Rate)
- Sharpe Ratio (risk-adjusted return)
- Beta (market sensitivity)
- Standard Deviation (volatility)
- Correlation Matrix

## Key Findings
- **Sun Pharma** was the best performer with a CAGR of +7.8%, beating the Nifty 50 (+3.2%) and achieving the highest Sharpe Ratio (0.23). Its low Beta of 0.54 made it the most defensive and best risk-adjusted stock in the portfolio.
- **HDFC Bank** marginally matched the benchmark at +3.0% CAGR but had a near-zero Sharpe Ratio indicating poor risk-adjusted returns.
- **Infosys** was the worst performer at -6.9% CAGR due to IT sector headwinds during this period.
- **Asian Paints** and **Reliance** both delivered negative returns at -5.9% and -3.1% respectively.
- The overall portfolio **underperformed the Nifty 50**, highlighting the importance of sector allocation and diversification.
- **Reliance (Beta 1.07)** and **HDFC Bank (Beta 1.01)** moved closely with the market while **Sun Pharma (Beta 0.54)** acted as a defensive hedge.

## Visualisations
- Portfolio Growth Chart vs Nifty 50
- Portfolio Allocation Pie Chart
- Correlation Heatmap
- Average Daily Returns Bar Chart
- Metrics Summary Table
