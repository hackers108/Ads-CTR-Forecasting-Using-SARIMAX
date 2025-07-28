#  Ads CTR Forecasting using SARIMAX

This project performs Click-Through Rate (CTR) analysis and forecasting using Python, Plotly, and SARIMAX time series modeling.

## What It Does
- Calculates daily CTR from ad impressions and clicks
- Analyzes trends and patterns (weekday vs weekend)
- Uses ACF/PACF for p, d, q value selection
- Forecasts CTR using SARIMAX (Seasonal ARIMA with exogenous support)
- Visualizes actual vs predicted CTR

##  Files Included
- `ads-ctr-forecasting-using-sarimax.ipynb`: Complete analysis notebook
- `ctr.csv`: The CTR dataset (optional)

##  Libraries Used
- `pandas`, `plotly`, `statsmodels`, `matplotlib`

##  Project Outcome
- Built a SARIMAX model to predict CTR for 100 days
- Identified patterns in CTR across weekdays/weekends
- Can be used by advertisers to optimize campaigns

> Built by **Arpit Yadav** | [Kaggle Notebook](https://www.kaggle.com/code/hacker108/ads-ctr-forecasting-using-sarimax)
