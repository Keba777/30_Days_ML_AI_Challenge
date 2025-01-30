# Day 13: Time Series Analysis

## What I Learned
- **Time Series Forecasting**:
  - Understanding the structure of time series data (trend, seasonality, noise).
  - Differences between stationary and non-stationary data.
- **ARIMA Model**:
  - Autoregressive (AR), Integrated (I), and Moving Average (MA) components.
  - Using ACF and PACF plots to determine model parameters.
- **Prophet Model**:
  - Facebook's Prophet for automatic trend and seasonality modeling.
  - Handling missing values and anomalies in time series data.
- **Stock Price Prediction**:
  - Collecting stock data using `yfinance` library.
  - Training ARIMA and Prophet models for forecasting.

## Tasks Completed
1. **Data Collection**:
   - Fetched historical stock price data using `yfinance`.
   - Preprocessed the data by handling missing values and outliers.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized stock price trends over time.
   - Analyzed seasonality and moving averages.
3. **Model Training & Forecasting**:
   - Implemented ARIMA for time series forecasting.
   - Applied Facebook Prophet for stock price prediction.
4. **Evaluation & Visualization**:
   - Compared forecast accuracy of both models.
   - Visualized predictions vs actual stock prices.

## Resources Used
- [ARIMA Model Guide](https://www.statsmodels.org/stable/generated/statsmodels.tsa.arima.model.ARIMA.html)
- [Facebook Prophet Documentation](https://facebook.github.io/prophet/)
- [Stock Data with yfinance](https://pypi.org/project/yfinance/)
- [Time Series Forecasting in Python](https://towardsdatascience.com/time-series-forecasting-using-arima-and-prophet-ebe249b2f831)
