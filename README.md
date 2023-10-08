# Pairs Trading Strategy Implementation with Python

In this project, we merge statistical techniques with financial theory to illuminate the application of a prevalent equity markets strategy: Pairs Trading.

## Objective

In this project, our ambitions are distinctly partitioned into the following developmental phases:

* **Part 1**: `Stationarity.ipynb`: Explore and define stationarity in time series data, highlighting its importance in financial analysis and examining statistical tests that verify the stationarity of stochastic processes.

* **Part 2**: `Mean_ReversionTesting.ipynb`: This section delves into mean reversion concepts, illuminated by real-world examples and proven through empirical testing, notably utilizing the Hurst exponent test to substantiate instances of mean reversion in financial time series.


* **Part 3**: `Ornsteiny_Uhlenbeck_process.ipynb`: Dive into the Ornstein-Uhlenbeck (OU) Process, generating it and scrutinizing its statistical properties. Furthermore, parameters of the model are inferred from a single path analysis using the OLS and MLE.


* **Part 4**: `Pairs_trading.ipynb`: Cointegration and Pairs Trading - Develop a model to identify cointegrated financial instruments and utilize this understanding to design and implement a pairs trading strategy, focusing on how cointegration facilitates the identification of viable trading pairs.


## Data Source

The data utilized in this project was retrieved from [Yahoo Finance](https://finance.yahoo.com/), a platform offering historical financial data free of charge. Data extraction was facilitated using the [yFinance](https://pypi.org/project/yfinance/) Python module.

