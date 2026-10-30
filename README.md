# Reliance Industries (NSE: RELIANCE) — Exploratory Data Analysis

A short, descriptive analysis of the daily price history of Reliance Industries Ltd.,
India's largest listed company by market capitalization, covering January 2008 to
October 2026.

## What this covers

- Long-term price history and compound annual growth rate
- Distribution of daily returns, compared against a normal distribution of the same
  mean and variance (skewness, excess kurtosis)
- Volatility over time, and how it clusters into calm and turbulent periods
- Price trend relative to 50-day and 200-day moving averages

## Key findings

- Daily returns are fat-tailed relative to a normal distribution (excess kurtosis
  ≈ 9.3) — large moves are more common than a normal-distribution assumption would
  suggest.
- Volatility is not constant: it clusters, with clear spikes around the 2008 global
  financial crisis and the 2020 COVID-19 selloff, followed by gradual decay.
- The single most extreme daily return in the sample (+21.4%, 2009-05-18) coincides
  with a specific, identifiable market event — the 2009 Indian general election
  result — rather than being a generic data artifact, a useful reminder that extreme
  observations in financial data are often explainable rather than noise.

## Data

Daily adjusted OHLCV prices from NSE (`data/RELIANCE.csv`), adjusted for splits,
bonus issues, and dividends.

## Running it

```
pip install pandas numpy scipy matplotlib jupyter
jupyter notebook notebook.ipynb
```

No internet access or API keys required — the dataset is included in this repository.
