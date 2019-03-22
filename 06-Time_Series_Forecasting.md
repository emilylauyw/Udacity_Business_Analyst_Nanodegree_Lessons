# 06 - Time Series Forecasting

## Fundamentals of Time Series Forecasting

### Time Series forecasting
- Time series forecasting is the use of a statistical model to predict future values based on past result.

### What kinds of variables can we forecast?
- Any variable that can be tracked and collected over time
- Example: Annual population data, company's daily stock price or quarterly sales figures

### Answer questions like:
- How do we define time?
- What are the trends?
- What are seasonal patterns?

### Order Matters
- There is a dependency on time and changing the order could change the meaning of the data.

### Objective
1. Identifying the patterns represented by the sequence of observations
2. Forecasting or predicting future values of the time series

### Time series is a sequence of data points with the following characteristics:
1. Covers a continuous time interval
2. Equal spacing between every two consecutive measurements
3. Each time unit within the time interval has at most one data point

### Average Method
- The best predictor of what will happen tomorrow is the average of everything that has happened up until now.

### Naive Method
- If there is not enough data to create a predictive model, the Naive method can supplement forecasts for the near future.

### Trend
- A gradual shift or movement to relatively higher or lower values over a long period of time.

![Trend](Screenshots/13.jpg "Trend")

### Seasonal pattern / Seasonality
- A time series that exhibits a repeating pattern at fixed intervals of time within a one year period.

### Cyclical Pattern
- Exist when data exhibits rises and falls that are not of a fixed period.

![Cyclical pattern](Screenshots/14.jpg "Cyclical")

![Bull vs Bear Market](Screenshots/15.jpg "Market")

### Cyclical vs Seasonal
- Cyclical: fluctuations are not of a fixed period. Avg length of cycles is longer than the length of the seasonal pattern. Magnitude of cycles tends to change more than the magnitude of season patterns.
- Seasonal: period is unchanging and associated with some aspect of the calendar.

## ETS Models (Exponential Smoothing)
- Use weighed averages of past observations, giving more weight to the most recent observation with weights gradually getting smaller as the observation gets older.

### E: Erorr, T: trend, S: Seasonality

### How do we determine how to apply the error, trend and seasonality terms of an ETS mode?

![Time series decomposition plot](Screenshots/16.jpg "Plot")

### Identifying Additive or Multiplicative terms

![Addition vs Multiplication](Screenshots/17.jpg "")

### Time Series Scenarios
- The possible time series (TS) scenarios can be recognized by asking the following questions:

#### TS has a trend?
- If yes, is the trend increasing linearly or exponentially?
- TS has seasonality?
- If yes, do the seasonal components increase in magnitude over time?

#### Scenarios
Therefore the scenarios could be:

- No-Trend, No-Seasonal
- No-Trend, Seasonal-Constant
- No-Trend, Seasonal-Increasing

- Trend-Linear,No-Seasonal
- Trend-Linear,Seasonal-Constant
- Trend-Linear,Seasonal-Increasing

- Trend-Exponential,No-Seasonal
- Trend-Exponential,Seasonal-Constant
- Trend-Exponential,Seasonal-Increasing

### ETS models
Four ETS models that can help forecast these possible time-series scenarios.

1. Simple Exponential Smoothing Method
2. Holt's Linear Trend Method
3. Exponential Trend Method
4. Holt-Winters Seasonal Method





## ARIMA Models (Autoregressive Integrated Moving Average)

## Analyzing and Visualizing Results
