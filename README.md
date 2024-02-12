# Fuel Consumption Regression and Time Series Forecasting

## Description
This repository contains code related to the prediction of fuel consumption using regression models and time series forecasting techniques. The aim is to analyze and predict fuel consumption based on various factors.

## Regression Models
In the context of regression models, the following algorithms were employed:

1. Bayesian Ridge Regression
2. Kernel Ridge Regression
3. Stochastic Gradient Descent Regression
4. Regression Artificial Neural Network (ANN) with 6 dense layers and ReLU activation function.

## Time Series Forecasting
The second approach involves time series forecasting, where the method of sliding window is employed to transform the unsupervised problem into a supervised one. Previous n timeseries observations are used to predict the vessel’s fuel consumption for the next point. The implementation is based on a Long Short-Term Memory (LSTM) model with 3 LSTM layers and 1 dense layer, using tanh as the activation function for the LSTM layers.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for academic and non-commercial purposes.
