# Stock-Price-Prediction
Aim : to create a model to get the prediction of the "New York Stock Exchange" 
The value of 2016 whole year is provided
80% of the value will be used to train the model, and the remaining 20% to test the model.

## Dataset consists of the following files:

## prices.csv: 
raw data, as-is daily prices. Most of the data spans from 2010 to the end of 2016, for companies new on the stock market, is shorter. Don't have the splits data

## prices-split-adjusted.csv: 
same as prices, but there have been added adjustments for splits.

## securities.csv: 
a general description of each company with the division on sectors

## fundamentals.csv: 
metrics extracted from annual SEC 10K fillings (2012-2016), should be enough to derive most of the popular fundamental indicators

## Stock Price Prediction - AM.ipynb
Python code which predict the stock price using RNN
