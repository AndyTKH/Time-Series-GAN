# GANs for Synthetic Time Series Data
GANs train a discriminator and generator networks in an adversarial setting so that the generator is able to generate high-quality samples that faithfully mimic a range of input data. In this notebook, we will train GANs on time series of S&P500 dataset to generate synthetic time series that have a significant potential for backtest of trading strategy. Generated synthetic time series data could solve the limited availability of historical market data and lower the risk of backtest overfitting for any trading strategy. We will go through the following steps in this project:

* Load in and pre-process the S&P500 dataset
* Define discriminator and generator networks
* Train these adversarial networks
* Visualize the loss over time and some sample, generated time series data 
