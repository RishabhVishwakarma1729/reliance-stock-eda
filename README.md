# Reliance Industries (NSE: RELIANCE) — Exploratory Data Analysis

- A short analysis of Reliance Industries' daily share price.
- Period: January 2008 to October 2026.
- Reliance is one of India's largest listed companies.

## What this covers

- Long-term price history and yearly growth rate.
- Daily returns, compared with a normal curve.
- Volatility over time.
- Price trend using 50-day and 200-day moving averages.

## Key findings

- The price grew about 7.7% a year (CAGR).
- Extreme days are more common than a normal curve predicts (kurtosis about 9.3).
- Volatility changes over time. It spiked in 2008 and 2020.
- The best day (+21.4% on 2009-05-18) matches the 2009 election result.
- So extreme days in market data often have a real cause.

## Data

- File: `data/RELIANCE.csv`.
- Daily prices from NSE.
- Adjusted for stock splits and bonus issues.

## How to run

- Install the libraries: `pip install pandas numpy scipy matplotlib jupyter`
- Open the notebook: `jupyter notebook notebook.ipynb`
- No internet or API key is needed. The data is in this repository.
