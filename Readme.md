## Timeseries Forecasting - Apple Stocks

This project attempts to use forecasting methods to predict the Apple stocks closing price in the future.
This is more of a playground for practicing different methods to use for forecasting. 

#### How to view
Currently there is a Jupyter notebook with notes and code which can be run.

#### Data
The data comes from the [IEX Trading](https://iextrading.com/developer/docs/#stocks) site which gets realtime stock price data.

#### Methods currently used:
These are a list of current forecasting models used:

* Naive approach
* Simple Average
* Rolling Average
* Simple Exponential Smoothing
* Holts Trend
* Holts Winter Trend
* S-ARIMA (Seasonal - Autoregressive Integrated Moving Average)

#### To Do
* I still need to implement an ARIMA based model, but the data is required to be stationary by applying differencing techniques. 
* Implement an Deep Recurrent Neural Network to predict prices. 

#### Contributing
If you have other forms of forecasting models that may help, it would be much appreciated, this is just a learning playground.