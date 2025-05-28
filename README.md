I built a model that uses ARIMA(X), SARIMA(X), and Auto-Arima to make predictions using 11 years of passenger data. This model uses the AR, I and MA values to make good predictions.
- The AR(Auto Regressive) predicts future values based on its own past values
- The I is the number of times we have to difference the data until it is stationary(constant mean and variance over time)
- The MA(Moving Average) predicts future values based on past errors, it helps correct over/under shooting in predictions

I built another model with sample data which is supposed to simulate how a company can predict future sales using past and future values. 
In the model we add an exogenous variable ad_spend which gives an insight into how adding or lowering advertisement funds will affect future sales. This uses the ARIMA order of AR, I and MA as well.

It should also be noted that a very good benefit of using these models is that they show us the effect of seasonality and trend in data, while also letting us manipulate each and comparing the effects.
