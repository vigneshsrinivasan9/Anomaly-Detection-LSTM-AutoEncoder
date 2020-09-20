ANOMALY DETECTION USING LSTM AUTOENCODER
-----------------------

Objective
----------------------

Goal of this project is to build and train a Long Short Term Memory based Autoencoder model to detect anomalies (i.e. sudden price changes) in the S&P 500 index data.This is implemented using Keras API with Tensorflow 2.0 as backend.

Data
----------------------
Source - https://www.kaggle.com/pdquant/sp500-daily-19862018 

Dataset includes two columns with one containing a daily timestamp and the second with the raw, un-adjusted closing prices for each day.

Requirements
----------------------
1) numpy
2) pandas 
3) Keras
4) Tensorflow 2.0
5) matplotlib
6) seaborn

RESULTS
----------------------
Autoencoder model was trained for 100 epochs and loss distribution was plotted to obtain a suitable threshold value (0.65) for identifying an anomaly. Test loss ~ 0.098

