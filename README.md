# time-series
This code performs time series analysis on visitor data, focusing on trend and seasonality.

Moving Average: It computes the trend using a moving average. Two functions handle odd and even window sizes (q).
Deseasonalizing: calculate_w_k removes the trend, returning the de-trended values (w_k).
Seasonality: calculate_g_k calculates seasonality by finding deviations from the average in w_k.
Plotting: It plots the trend and seasonality components for visualization.
The data used represents daily visitor counts over a week.
