# Time Series Analysis Project

This project aims to demonstrate the understanding and application of time series analysis techniques for prediction and forecasting. We will use the "karachi-weather-2021-2023.csv" dataset to perform time series analysis and draw insights related to the provided questions.

## Project Overview

The main objective of this project is to apply time series analysis techniques to the "karachi-weather-2021-2023.csv" dataset. The dataset contains information about weather data in Karachi for the years 2021 to 2023. By performing time series analysis, we will explore the trends, seasonality, and residuals of the data, split it into train and test sets, and compare the performance of various forecasting methods.

### Dataset Description

The "karachi-weather-2021-2023.csv" dataset is provided as the input for this project. It includes information about weather data in Karachi, such as temperature, humidity, wind speed, and precipitation. We will utilize this dataset to perform time series analysis and draw insights related to the provided questions.

### Project Tasks

The project can be divided into the following tasks:

1. Data aggregation:
   - Aggregate the data into weekly mean using the `.resample('W').mean()` method.

2. Data visualization:
   - Read the dataset and visualize the trends, seasonality, and residuals.
   - Discuss your observations in the visualization and provide insights.

3. Train-test split:
   - Split the data into train and test sets.
   - Use all the data for 2021-2022 for training and 2023 for testing.

4. ARIMA modeling:
   - Use the ARIMA model to forecast the data.
   - Visualize the results and report the Root Mean Squared Error (RMSE).

5. SARIMA modeling:
   - Use the SARIMA model to forecast the data, considering the seasonal component with `seasonal_order=(0, 0, 0, 52)` (52 weeks in a year).
   - Visualize the results and report the RMSE.

6. Optimize SARIMA parameters:
   - Try to find the optimal parameters for the SARIMA model.
   - Pick the best parameter combination, visualize the results, and report the RMSE.
   - Compare the performance of ARIMA and SARIMA models and conclude which one is better.

7. Machine Learning regression models:
   - Use two Machine Learning regression techniques on the same training and testing sets used for ARIMA and SARIMA.
   - Visualize the results and report the RMSE for each model.

8. Compare RMSEs:
   - Compare the RMSE values obtained from ARIMA, SARIMA, and the two regression algorithms.
   - Discuss which model performs better for this specific time series analysis task.

9. Future price prediction with SARIMA:
   - Generate future dates (weekly) from April 1st, 2023 to December 31st, 2023 using the `pd.date_range()` function.
   - Predict the price using the SARIMA model with the optimal parameters obtained in the previous step.

10. Future price prediction with ML regression:
    - Using the same future dates generated in the previous step, predict the price using any one of the ML regression models.

11. Visualization and comparison of predictions:
    - Visualize the predictions from the SARIMA model and the ML regression model for the future dates.
    - Discuss the differences between the predictions and provide insights.
