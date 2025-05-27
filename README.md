I built a model that uses ARIMA(X), SARIMA(X), and Auto-Arima to make predictions using passenger dataset for 11 years. This model uses the AR, I and MA values to make the 
predictions accurate.
  The AR(Auto Regressive) is the predicted values based on past values, 
  The I is the number of times we have to difference the data until it is stationary(constant mean and variance over time)
  The MA(Moving Average) predicts future values based on past errors, it helps correct over/under shooting in predictions

I built another example with sample data which is supposed to simulate how a company can predict future sales based on past ad spend and future ad spend values. 
In the model we use an exogenous value ad_spend which gives an insight into how adding or lowering ad_spend will affect future sales. This also uses the ARIMA order of AR, I and MA.

It should also be noted that a very good benefit of using this model is that it shows us the effect of seasonality and trend in data while also letting us remove each and viewing results.
