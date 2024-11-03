# Time-Series-Analysis-Project
 Forecasting Stock Prices Using ARIMA Models

*Objectives:*
> Predict future stock values based on historical data.
>Understand the trend, seasonality, and other patterns in the time series.
> Evaluate the performance of ARIMA models.
> Provide accurate forecasts for decision-making.

*Project Steps:*
1. Environment Setup:
> Clear the environment (remove any existing variables).
> Load necessary Python libraries (e.g., pandas, numpy, statsmodels).
> Read the dataset.
2. Exploring Data:
> Create and plot the time series data using matplotlib.pyplot.
> Evaluate the series plot to identify any visible trends, Stationarity or seasonality.
3. Log Transformation:
> Apply a log transformation to the series.
4. Stationarity Test:
> Check if the series is stationary (e.g., Augmented Dickey-Fuller test).
> If not stationary, perform differencing.
5. Identify ARIMA Parameters (ACF & PACF)
> Hyperparameter Tuning using Grid search Using train and test dataset
> Evaluate the model using  AIC and MSE.
6. ARIMA Modeling:
> Fit the Best ARIMA Model
> Model Evaluation: Residual Analysis
7. Forecasting:
> Generate stock price forecasts using the chosen ARIMA model.
