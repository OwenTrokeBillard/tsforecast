# YYC PyData Time Series Forecasting
Time series forecasting for Nov 29, 2018 meetup. Presentation on traditional and ML forecasting tools, 
some important concepts to familiarize yourself with, and a few techniques and strategies related to testing
and evaluation of forecasting models.

## Workshop
Use macroeconomic data from the US to try and predict nominal GDP growth (in the US). GDP data is taken from ~1950 and macroeconomic data begins at various periods.

The sample notebook references some common libraries and offers a brief explanation of some of the features contained in the data set

Some example problems to try on:
- Try using GDP alone in an ARIMA model using the statsmodels package. 
  - Try adding in simple exogenous series such as the credit_impulse or lei field to see how it changes
- Perform feature engineering on your favourite exogenous features and lagged GDP variables. Create a linear regression model such as ElasticNet or LinearSVR from the sklearn package
- Try out the vector autoregressive package from statsmodels to account for interdependcy amongst the features
- Have a go with LSTMs if you're feeling particularly inspired


Meetup link:
https://www.meetup.com/PyData-Calgary/events/255946858/

