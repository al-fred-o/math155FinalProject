# math155FinalProject

This project was completed in the spring semester 2021 for a Time Series Analysis course at Harvey Mudd College. 
Done in collaboration by [Alfredo Gomez](https://al-fred-o.github.io/) and [Steven Litvack-Winkler](https://github.com/stevenlw-porpoise).

#### Abstract
We describe a time series model for the total electricity consumption of the United States from 2008
through 2018. We found that that an ARIMA(0, 1, 1) × ARIMA(1, 1, 1)12 model best fits the data and
passes the runs, Shapiro-Wilk, and Box-Ljung tests. Applying the forecast of the model to 2019 through
the present, we see that the actual data falls within the 95th-percent confidence band of the forecast. We
take similar steps to model the electricity consumption of the commercial sector over the same time period
and reach a slightly different ARIMA(2, 0, 0) process, accounting for seasonality with monthly means and
time since the start of the series as regressors. While the model does not pass pass the Shapiro-Wilk test,
performs fairly well under other metrics. The final model is also able to predict most of the data fairly
well, with the exception of March and April 2020, which falls outside of the models forecast. However,
this behavior is expected as a result of US COVID-19 lockdown restrictions during this time.
