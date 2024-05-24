# Divvy-Demand-Forecast

1. Background

* Explain the concept of bike-sharing systems and introduce Divvy Bikes as a significant player in urban mobility.
Discuss the relevance of predicting bike demand (e.g., for maintenance, availability, and strategic deployment).

3. Data Overview

* Mention the source and range of the data (March 2020 to March 2024).
Types of bikes covered: classic, electric, and docked.

3. Models Used

* ARIMA/SARIMA: Autoregressive Integrated Moving Average (ARIMA) and its seasonal variant (SARIMA) are classical statistical models for time series forecasting. They are particularly effective for data with clear trends and seasonal patterns.
* Facebook Prophet: Developed by Facebook, this model is robust for datasets with strong seasonal effects and holidays. Prophet is user-friendly, handling missing data and outliers well, and it can automatically detect changes in trends.
* Uber Orbit: A modern Bayesian framework designed to provide fast and flexible inference for time series data. The Damped Local Trend (DLT) model within Orbit is excellent for capturing non-linear growth and accommodating seasonality.
* LSTM (Long Short-Term Memory): A type of recurrent neural network well-suited to classifying, processing, and predicting time series given time lags of unknown duration. Ideal for data where the relationship between time steps is crucial.
