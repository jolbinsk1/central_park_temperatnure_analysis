# Central Park Temperature Analysis

This project analyzes the historical temperature data of Central Park, New York, using time series analysis techniques like seasonal decomposition, moving averages, and SARIMA modeling. The analysis is conducted within a Jupyter Notebook to make it easier to follow and visualize results.

## Project Overview

The project follows these main steps:

- Data Extraction: Download temperature data from a PDF provided by the National Weather Service.
- Data Preprocessing: Convert the data into CSV format and clean it up for analysis.
- Data Analysis: Visualize trends, decompose seasonal patterns, and examine autocorrelations.

Modeling: Apply and compare different models, including:
Simple Moving Average (SMA)
Exponentially Weighted Moving Average (EWMA)
Exponential Smoothing (Double and Triple)
SARIMA for time series forecasting
Evaluation: Assess the performance of models and forecast future temperature trends.
Table of Contents

pandas
numpy
requests
tabula-py
matplotlib
statsmodels
pmdarima
jupyterlab  # or jupyter if preferred

Data Source

The temperature data is sourced from the National Weather Service - New York, NY Office. The data is provided in PDF format, which is converted into CSV for analysis.

## Usage

1) Open the Jupyter Notebook:
- Once Jupyter is running, open CentralParkTemperatureAnalysis.ipynb in your browser. Each step of the analysis, from downloading the data to forecasting future temperatures, is documented in the notebook.
2) Run the Cells:
- The cells can be executed sequentially to follow along with the analysis.
- The notebook includes various time series analyses, such as seasonal decomposition, autocorrelation plots, and different forecasting models.
3) Modify Parameters:
- If you'd like to experiment with different models or configurations, feel free to modify the relevant cells in the notebook and re-run them.
 
### Modeling Techniques

Simple Moving Average (SMA): Calculated over a 12-month window to smooth temperature trends.
Exponentially Weighted Moving Average (EWMA): Focuses more on recent values by applying exponentially decreasing weights.
Double & Triple Exponential Smoothing: Capture both trend and seasonality in the data.
SARIMA (Seasonal ARIMA): A time series forecasting model that accounts for both autoregressive and moving average components, as well as seasonality.
Results

Seasonal Decomposition: Displays a strong seasonal pattern in Central Park’s temperature data.
Triple Exponential Smoothing: Provides a better fit than double smoothing for seasonal data.
SARIMA Model: Achieves a lower RMSE (Root Mean Square Error) compared to other models and is used for forecasting future temperatures.
Future Enhancements

Potential future improvements include:

Automating hyperparameter tuning for SARIMA or other forecasting models.
Adding external factors such as humidity or pressure to improve forecast accuracy.
Exploring machine learning models, such as LSTM or Prophet, for more robust predictions.
Enhancing visualizations with interactive plots using libraries like Plotly.
