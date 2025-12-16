# Bitcoin Sentiment Prediction
### Measuring the Predictive Relationship Between Investor Sentiment and Next-Day Bitcoin Returns 

Stats 140XP final project analyzing whether investor sentiment predicts next-day Bitcoin returns.

## Overview
This project studies the relationship between daily investor sentiment, measured by the Crypto Fear & Greed Index, and next-day Bitcoin log returns. The analysis uses a predictive (lagged) framework to avoid contemporaneous price–sentiment bias and focuses on short-horizon return behavior in cryptocurrency markets.

## Data
- Crypto Fear & Greed Index (Alternative.me)
- Bitcoin price data (CoinCodex)
- Daily observations from 2018–2025

## Methodology
- Log returns computed from daily closing prices
- Sentiment analyzed as:
  - Continuous index
  - Categorical sentiment bins
- OLS regression with lagged sentiment
- Newey–West standard errors to address autocorrelation and heteroskedasticity

## Repository Structure
data/ # raw and processed datasets
notebooks/ # EDA and regression analysis
figures/ # plots used in paper
paper/ # final paper
slides/ # presentation slides


## Tools
Python (Pandas, NumPy, statsmodels, matplotlib)

## Author
Kimberly Cui
