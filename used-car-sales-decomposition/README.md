# Used Car Sales Decomposition & Forecasting

## Overview
This project analyzes U.S. Used Car Dealer Sales (1992–2025) using time series techniques in R.

The dataset is sourced from FRED (MRTSSM44112USN) and is not seasonally adjusted.

## Methods Used
- Time Series Visualization
- Autocorrelation Function (ACF)
- Classical Decomposition (Multiplicative)
- X-11 Decomposition
- ETS Forecasting (12-month horizon)

## Key Findings
- The series exhibits a strong upward long-run trend.
- Clear seasonal patterns appear annually.
- A significant irregular shock occurs around 2020 (COVID-19 period).
- Seasonally adjusted forecasts provide a smoother view of underlying economic trends.

## Tools & Packages
- R
- quantmod
- forecast
- seasonal
- ggplot2

## Live Project
View the full interactive HTML report here:

👉 https://bleona-k.github.io/analytics-portfolio/used-car-sales-decomposition/
