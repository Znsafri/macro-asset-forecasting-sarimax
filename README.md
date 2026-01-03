# macro-asset-forecasting-sarimax
Time-series forecasting of S&amp;P 500 and Gold prices using SARIMAX (2026 outlook)
# Macro Asset Forecasting using SARIMAX (2026 Outlook)

This project applies SARIMAX time-series models to forecast:
- **S&P 500 Index**
- **Gold Prices**

using monthly data through 2025, with probabilistic forecasts for 2026.

## Assets Covered
- S&P 500 Index (^GSPC)
- Gold Futures (GC=F)

## Methodology
- Monthly data from Yahoo Finance
- Stationarity testing using Augmented Dickey-Fuller
- SARIMAX modeling with confidence intervals
- Forecast horizon: 12 months (2026)

## Results

### S&P 500 Forecast (2026)
![S&P 500](figures/sp500_2026_forecast.png)

### Gold Forecast (2026)
![Gold](figures/gold_2026_forecast.png)

## Notes
- This is not a trading strategy
- Intended for macro trend analysis and uncertainty assessment

## Tools
Python, pandas, statsmodels, yfinance, matplotlib
