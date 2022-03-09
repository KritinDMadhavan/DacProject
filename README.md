# Problem Statement 
The project aims at providing a model to predict the rainfall for a region in india based off historiacal data. 

## Dataset

The dataset used is the [Rainfall in India](https://www.kaggle.com/rajanand/rainfall-in-india) from Kaggle.

**Target Variables: January - December**
<br>
<br>
Each column from January to December has the rainfall received correspoinding to the year mentioned in the row from 1901 to 2015
<br>
**Mean Selling Price:** 121,000$
<br>
**Max Selling Price:** 1,000,000$
<br>
**Min Selling Price:** 45,000$


## Model(s) Used

The models that are to be used in this project are:
<br>
<br>
*ARIMA Model: *
An autoregressive integrated moving average, or ARIMA, is a statistical analysis model that uses time series data to either better understand the data set or to predict future trends. A statistical model is autoregressive if it predicts future values based on past valuesThe first step in building the ARIMA model is to create an autocorrelation plot on stationary time series data.
<br>
<br>
*ETS Model*
Exponential Smoothing (ETS) is a commonly-used local statistical algorithm for time-series forecasting. We will be comparing the results of the ARIMA and the ETS Models to find the one with a better fit

## Future Work
Implementation of the ETS and ARIMA models and the deployment framework
