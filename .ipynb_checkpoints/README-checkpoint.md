# Time Series - A Yen for the Future


## Time Series Forecasting
Completed the following as outlined in the starter notebook:

a) Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).

b) Forecasting Returns using an ARMA Model.

c) Forecasting the Settle Price using an ARIMA Model.

d) Forecasting Volatility with GARCH.

Answers to questions:

1) Based on your time series analysis, would you buy the yen now?
Yes, the time series forecast shows positive returns (ARMA model) and increase in settle price (ARIMA model) in the next 5 days.

2) Is the risk of the yen expected to increase or decrease?
Based on the Garch model, risk is expected to increase.

3) Based on the model evaluation, would you feel confident in using these models for trading?

The ARMA and ARIMA models had p-values that are above the significance level of 0.05 whilst the Garch model had a more acceptable p-level. I would like to test the models out (probably more data) before using these in actual trading.

## Linear Regression Forecasting

Built a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with lagged Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).

Completed the following as outlined in the starter notebook:

a) Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)

b) Fitting a Linear Regression Model.

c) Making predictions using the testing data.

d) Out-of-sample performance.

e) In-sample performance.

Answer to question:

Does this model perform better or worse on out-of-sample data compared to in-sample data?
The model performs better on out-of_sample data as the root mean squared error is 0.415 as compared to the in_sample data which has a root mean square error of 0.596.