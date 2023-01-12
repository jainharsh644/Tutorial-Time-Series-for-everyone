<figure>
    <img src="https://github.com/jainharsh644/Tutorial-Time-Series-for-everyone/blob/main/Timeseries.png" alt="SAE" title="" />
</figure>

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 

# Tutorial-Time-Series-for-everyone

# Introduction:
<p>Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data. Time series forecasting is the use of a model to predict future values based on previously observed values.</p>

# Components of a Time Series:
<ul>
    <li><b>Trend:</b> Trend is a pattern in data that shows the movement of a series to relatively higher or lower values over a long period of time. Trend usually happens for some time and then disappears, it does not repeat. For example, some new kaggle kernels, it goes trending for a while, and then disappears. There is fairly any chance that it would be trending again.</li>
    <li><b>Seasonality:</b> Predictable pattern that recurs or repeats over regular intervals. Seasonality is often observed within a year or less.</li>
</ul>

# ARIMA, SARIMA Models:
## ARIMA:
<ul>
<li>Autoregressive Integrated Moving Average, or ARIMA, is a forecasting method for univariate time series data.</li>
<li>As its name suggests, it supports both an autoregressive and moving average elements. The integrated element refers to differencing allowing the method to support time series data with a trend.</li>
<li>A problem with ARIMA is that it does not support seasonal data. That is a time series with a repeating cycle.</li>
<li>ARIMA expects data that is either not seasonal or has the seasonal component removed, e.g. seasonally adjusted via methods such as seasonal differencing.</li>
</ul>

## SARIMA:
<ul>
<li>Seasonal Autoregressive Integrated Moving Average, SARIMA or Seasonal ARIMA, is an extension of ARIMA that explicitly supports univariate time series data with a seasonal component.</li>
<li>It adds three new hyperparameters to specify the autoregression (AR), differencing (I) and moving average (MA) for the seasonal component of the series, as well as an additional parameter for the period of the seasonality.</li>
<li>A seasonal ARIMA model is formed by including additional seasonal terms in the ARIMA.</li>
<li>The seasonal part of the model consists of terms that are very similar to the non-seasonal components of the model, but they involve backshifts of the seasonal period.</li>
</ul>

# Please do ⭐ the repository, if it helped you in anyway.
