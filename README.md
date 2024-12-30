
# Time Series Analysis with Prophet

This repo aims to analyze the results using the time series analysis technique for Prophet from Meta (Facebook).
Even though I will show my approach to predicting the future values of a stock, I would like to explain others' approaches:

1) ARIMA is a traditional approach to check this type of analysis.
2) LLM will check its behavior to predict values and plot graphs.

## Prophet

A traditional approach to time series is the, a.k.a. ARIMA, based on autoregressive and mobile averages and an integrator factor to not stationary series.
Instead, I will use the library Prophet [1], which analyzes time series through Machine Learning.

### 2.1) Introduction

This type of series does not show regularity, such as the behavior of a CPU. It is the typical manner of stock options, a measure of earth shake, etc.

I aim to use the Prophet model, based on Machine Learning, to predict the future values of stock options; in this case, I have chosen Nubank. Let's start.

### 2.2) Code

Please refer to ts_prophet_v3.ipynb file.
This file has a lot of figures, and due to that, I suggest opening the file on https://nbviewer.org/ and past this address as follows:

2.2.1) Open the URL: https://nbviewer.org/

2.2.2) Copy this address: _https://github.com/miltondsantos/TimeSeries_ARIMA_Prophet_LLM/blob/main/ts_prophet_v3.ipynb_

**Reference**

[1]  TAYLOR, S. J. and Letham, B. THE AMERICAN STATISTICIAN. 2018, VOL. 72, NO. 1, 37–45
