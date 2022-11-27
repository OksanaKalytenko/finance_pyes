# finance_pyes

A collection of various finance related projects. They are all in separate jupyter notebooks that contain basic examples of all the topics that I was interested to explore.
In the following you have short links and descriptions of all my projects. 

Have fun exploring yourself! Feel free to experiment with everything you find! 🙃

## [Analysis of BTC Returns](Analysis_of_BTC_Returns.ipynb)

In this notebook we gather our financial data and preprocess it into the form that is most commonly used in real-life projects.

We use CoinGecko to obtain our historical data. 
You may find other sources such as Yahoo Finance, Coinmarketcap or Alpha Vantage as good alternatives too.
Just keep in mind that data differs among sources as the respective sites also get their data from different sources and might use other methods to adjust the prices for corporate actions.

Once we prepare our historical data, we will investigate whether it follows certain patterns (called stylized facts) commonly observed in financial assets.

In this notebook we cover the following topics:

- Getting data from CoinGecko
- Converting prices to returns
- Financial Data and Preprocessing
- Visualizing time series data
- Identifying outliers
- Investigating stylized facts of asset returns

## [Optimisation and more](Optimisation_and_more.ipynb)

In this notebook I do some basic portfolio optimisation and statistical analysis.
My universe of securities is pretty short here (only 14 stocks), but you should get the idea. For better performence try to use a larger amount.

Also I have provided code to get financial data using different API (yahoo finance and quandl). But I like to work with yfinance 😊

## [Stock Signal Example Predictions](Stock_Signal_Example_Predictions.ipynb)

I am really found of financial markets.
After reading some books, learning some machine learning tools, joining Datacrunch community and working with their datasets using various ML models, I've got inspired to create this notebook.

The idea here is to get live quotes for a stock, create features (using RSI, Moving Averages, etc)
Then train a simple tree model on those features against the custom target.

You can use different API for finance data (yahoo finance, quandl etc)

## [Time Series Modeling with ARIMA](Time%20Series%20Modeling%20with%20ARIMA.ipynb)

In this notebook, we go through the basics of time series modeling.

We explore the building blocks of time series and how to separate them using some decomposition methods.
We introduce the concept of stationarity and why it is important, how to test for it, and ultimately how to achieve it in case the original series is not stationary.
We also look into the most widely used approach to time series modeling — ARIMA class models.

We cover the following:

- Decomposing time series
- Correcting for stationarity in time series
- Modeling time series with ARIMA class models
- Forecasting using ARIMA class models

We will explore everything mentioned above using Weekly Apple's stock prices in 2015-2022.
