# Time-Series-Analysis-Project
 Forecasting CPI Using ARIMA Models

*Objectives:*
> Predict future CPI values based on historical data.
>Understand the trend, seasonality, and other patterns in the CPI time series.
> Evaluate the performance of ARIMA models.
> Provide accurate forecasts for decision-making.

*Project Steps:*
1. Environment Setup:
> Clear the environment (remove any existing variables).
> Load necessary Python libraries (e.g., pandas, numpy, statsmodels).
> Read the CPI dataset.
2. Exploring Data:
> Create and plot the time series data using tsplot.
> Evaluate the series plot to identify any visible trends or seasonality.
3. Trend Analysis:
> Fit a regression model to evaluate the trend.
> Compare fitted values with actual data.
4. Log Transformation:
> Apply a log transformation to the CPI series (1993Q1 to 2020Q3).
> Re-fit the log-transformed series using linear regression.
5. Classical Decomposition:
> Decompose both the original CPI series and the log-transformed CPI series (1993Q1 to 2020Q3).
> Explore additive and multiplicative decomposition.
6. X11 Decomposition:
> Apply the X11 decomposition analysis to the time series (2000Q1 to 2012Q4).
7. Stationarity Test:
> Check if the series is stationary (e.g., Augmented Dickey-Fuller test).
> If not stationary, perform differencing.
8. ARIMA Modeling:
> Fit an ARIMA model to the log-transformed CPI series.
> Evaluate the model using ACF plots and other diagnostics.
> Consider different ARIMA orders (e.g., ARIMA(2,1,2)(1,1,1))1.
9. Auto ARIMA:
> Use the auto.arima function to automatically select optimal ARIMA parameters.
10. Forecasting:
> Generate CPI forecasts using the chosen ARIMA model.
> Compare actual vs. forecasted values.
