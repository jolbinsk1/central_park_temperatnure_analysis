# Central Park Temperature Analysis

This project analyzes the historical temperature data of Central Park, New York, using time series analysis techniques like seasonal decomposition, moving averages, and SARIMA modeling. The analysis is conducted within a Jupyter Notebook to make it easier to follow and visualize results.

## Project Overview

Modeling: Apply and compare different models, including:
- Simple Moving Average (SMA): Calculated over a 12-month window to smooth temperature trends.
- Exponentially Weighted Moving Average (EWMA): Focuses more on recent values by applying exponentially decreasing weights.
- Double & Triple Exponential Smoothing: Capture both trend and seasonality in the data.
- SARIMA (Seasonal ARIMA): A time series forecasting model that accounts for both autoregressive and moving average components, as well as seasonality.

Evaluation: Assess the performance of models and forecast future temperature trends.

## Data Source

The temperature data is sourced from the National Weather Service - New York, NY Office. The data is provided in PDF format, which is converted into CSV for analysis.

## Usage

1) Open the Jupyter Notebook:
    - Once Jupyter is running, open the file in your browser. Each step of the analysis, from downloading the data to forecasting future temperatures, is documented in the notebook.
2) Run the Cells:
    - The cells can be executed sequentially to follow along with the analysis.
    - The notebook includes various time series analyses, such as seasonal decomposition, autocorrelation plots, and different forecasting models.
3) Modify Parameters:
    - If you'd like to experiment with different models or configurations, feel free to modify the relevant cells in the notebook and re-run them.
 
## Results

- Seasonal Decomposition: Displays a strong seasonal pattern in Central Park’s temperature data.
- Triple Exponential Smoothing: Provides a better fit than double smoothing and EWMA for seasonal data.
- SARIMA Model: Achieves a lower RMSE (Root Mean Square Error) compared to other models and is used for forecasting future temperatures.

