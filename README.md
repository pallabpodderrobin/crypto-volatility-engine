# Crypto Volatility Engine

Bitcoin daily return analysis using pure NumPy vectorization — no for loops.

## What this project does
- Loads 1-minute Bitcoin price data (2012–2015)
- Converts to daily closing prices using Pandas
- Calculates daily return % using NumPy (no loops)
- Detects volatile days where price moved more than 10%
- Visualizes returns and price history

## Key findings
- 65 volatile days (>10% swing) found in 1204 trading days
- Worst day: -53.84% (April 11, 2013)
- Best day: +35.81% (April 12, 2013)
- Most volatility clusters around the 2013 Bitcoin bubble

## Chart
![Bitcoin Volatility](btc_volatility.png)

## Tech stack
- Python
- NumPy — vectorized calculations
- Pandas — data cleaning and groupby
- Matplotlib — visualization

## How to run
```bash
pip install numpy pandas matplotlib
python crypto_volatility.py
```
