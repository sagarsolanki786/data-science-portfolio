Please click this link, https://bit.ly/2mx3xLJ to view this notebook in nbviewer.

Predict the spot exchange rates for the Euro into US dollars using the Bank of England's statistics.

1. The data is first analyzed to find out features such as trend and stationarity. It is then resampled by week and logarithmic differencing is performed to make it stationary which is confirmed by the Dickey-Fuller test.
2. ACF and PACF are applied to find the parameters for the ARIMA model along with residual analysis.
3. The differenced data is converted back to the original scale.
4. The ARIMA model is applied to the data and a Root Mean Square Error of 0.1353 is achieved.
5. The data is then split into train and test samples to check the accuracy of the model.
6. Model validation is performed by comparing its out-of-sample predictions with the actual values.
7. Finally, forecasted predictions are plotted with the data to visualize the Euro into USD.
