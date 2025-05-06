# Time Series Forecasting with AirPassengers Dataset 📈 
Forecasting Monthly Airline Passengers Using ARIMA in Python

🧩 Project Summary

This project involves analyzing and forecasting airline passenger traffic using monthly data from 1949 to 1960 (AirPassengers.csv). The goal was to build a forecasting pipeline using Python and ARIMA modeling, addressing time series challenges like non-stationarity and seasonality.

🔧 Tools & Technologies :
Python, pandas, matplotlib, statsmodels

## Key Steps
1. Data Preprocessing:
Loaded data using pandas and parsed Month as a datetime index.
Verified data integrity: 144 entries, no missing values, correct types.

2. Time Series Handling:
Extracted the #Passengers column as a Series.
Demonstrated various indexing methods for time-based slicing.

3. Stationarity Check:
Plotted the time series to identify trend and seasonality.
Observed a non-stationary pattern, requiring transformation.

4. ARIMA Forecasting:
Implemented ARIMA via statsmodels.
Generated a 156-month forecast, visualizing predictions alongside historical data.
Applied log transformation to stabilize variance.

5. Visualization & Interpretation:
Used matplotlib to display trends and forecast results.
Confidence intervals reflected increasing uncertainty over time.

✅ Outcome
The ARIMA model effectively captured historical trends and seasonal behavior, providing reliable long-term forecasts. The project demonstrated a practical and complete pipeline for time series forecasting, suitable for applications like transportation planning and demand forecasting.
