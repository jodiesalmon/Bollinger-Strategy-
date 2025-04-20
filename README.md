# Bollinger-Strategy-
Basic backtest of a mean reversion strategy using Bollinger Bands on Microsoft stock with Python.

# Bollinger Bands Mean Reversion Strategy

This project explores a basic mean reversion trading strategy using Bollinger Bands on Microsoft (MSFT) stock data from 2019 to 2023.

The strategy assumes that prices tend to revert back to the mean, so it:
- **Buys** when price falls below the lower Bollinger Band
- **Sells** when price rises above the upper Bollinger Band

### 🛠 Tools & Libraries
- Python
- yfinance (for stock data)
- pandas (for data analysis)
- matplotlib (for visualisation)

### 📈 Strategy Logic
- 20-day Moving Average (MA)
- Upper/Lower Bands = MA ± 2 standard deviations
- Entry signals are generated when the price crosses the bands

### 📊 Output
- A chart showing MSFT’s price + Bollinger Bands
- A comparison of cumulative returns from:
  - Holding the stock
  - Following the strategy

---

### 🔍 Learning Goals
This notebook demonstrates:
- How to apply technical indicators in Python
- How to generate and test trading signals
- Simple backtesting using historical data
