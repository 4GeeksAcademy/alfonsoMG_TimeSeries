# Time Series Analysis and Forecasting

This repository contains a Jupyter Notebook (`ts.ipynb`) that demonstrates a comprehensive analysis and forecasting of time series data. The script is located in the `/src` directory. The original raw data can be found in '/data' and the model has been saved in the '/models' directory.

## Overview

The provided Jupyter Notebook (`ts.ipynb`) guides through the following steps:

1. **Data Preprocessing:** Transforming the 'date' column to the 'datetime' format to facilitate proper handling of the dataset.

2. **Trend Analysis:** Visualizing and analyzing the trend, which is characterized by a consistent upward progression.

3. **Seasonality Detection:** Utilizing the Dickey Fuller test to determine seasonality in the dataset.

4. **Residual Analysis:** Confirming the presence of residuals with a similar intensity to the original dataset's fluctuations.

5. **Autocorrelation Analysis:** Identifying a high autocorrelation, with a gradual tendency to decrease.

6. **Model Training:** Implementing the auto_arima model, explicitly considering the non-stationary nature of the dataset.

7. **Prediction:** Forecasting the next 20 days using the trained model.

8. **Summary:** Evaluating the model's performance, acknowledging its success in capturing the trend, and discussing the absence of noise in predictions.
