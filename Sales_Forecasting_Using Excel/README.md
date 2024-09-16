# Forecasting using Excel

Forecasting is a technique used to predict future values based on historical data.

It involves analyzing past trends, patterns, and relationships to estimate what might happen in the future.

For example, sales forecasting, use sales data to predict future sales. 

This could involve:

Analyzing trends: Identifying upward or downward trends in sales over time.

Identifying seasonal patterns: Determining if sales fluctuate based on seasons or holidays.

Considering external factors: Examining how factors like economic conditions or marketing campaigns might impact sales.

## Home Depot Sales Forecasting Project

## Project Overview
This project focuses on forecasting future sales based on historical sales data from Home Depot. 

## Dataset

**Source: Home Depot's quarterly sales data**

**Quarter**: The fiscal quarter of the year.

**Date:** The specific date for the quarter.

**Sales:** The sales figures for the quarter.

**Time Period:** 2012 to 2021

## Objective

The main objective of this project is to create a sales forecast for the upcoming quarters using the provided historical sales data. 

## Methodology

(1) Data Preparation

(2) Data Loading: Import the dataset into Excel.

(3) Data Cleaning: Ensure there are no missing values or anomalies in the dataset.

(4) Data Structuring: Organize the data in a tabular format suitable for analysis.

## Data Visualization

**Line Chart**: 

Use a line chart to visualize the historical sales data.

Plotting the sales data to get a clear overview of historical trends

![Historical Data](https://raw.githubusercontent.com/AthiraThulasi/Excel/main/Sales_Forecasting_Using%20Excel/Historical_Data.png)


## Forecasting

**Forecasting Algorithm:**

The forecast sheet in Excel uses the **Exponential Triple Smoothing (ETS) algorithm**, which is effective for time series forecasting.

  =FORECAST.ETS(forecast_date, known_y_values, known_x_values).

Retrieves Data: Excel retrieves the values in the known_y_values and known_x_values ranges. These ranges typically contain your historical data.

Applies Algorithm: Excel applies the Exponential Triple Smoothing algorithm to analyze the historical data and identify trends, seasonality, and other patterns.

Calculates Forecast: Based on the analysis, Excel calculates the forecasted value for the specified forecast_date.

Returns Result: Excel returns the calculated forecast value to the cell where you entered the formula.
  
  ETS: Exponential Triple Smoothing algorithm smooths the data by considering trends, seasonality, and noise, providing a reliable forecast for future values.

![Future Predictions](https://raw.githubusercontent.com/AthiraThulasi/Excel/main/Sales_Forecasting_Using%20Excel/Future_predictions.png)
 
 ## Analysis
 
 **Overall Trend:**
 
 The forecasted values indicate a continuing upward trend in Home Depot's quarterly sales. This suggests sales are expected to keep going up in the coming months.

**Growth Rate:**

Sales have been going up from $32,261 in January 2021 to $44,740 in July 2023, which is a good sign for Home Depot's positive market performance and strong consumer demand.

**Seasonal Patterns:**

The forecast shows sales are higher in the summer (quarter 2 and 3) just like they have been in the past. This helps Home Depot decide what to stock and advertise at different times of the year.

**Taking Action Based on the Forecast**

Since sales are expected to go up and there are clear busy seasons, Home Depot should:

(1) Make sure they have enough of what customers want, especially during busy times.

(2) Run ads at the right times to get the most out of their marketing budget.

**Operational Planning:**

If sales are expected to rise, Home Depot might need to

(1) Hire more staff to handle the extra customers.

(2) Stock up on more products to avoid running out.

(3) Improve their delivery system to get things to customers faster.

**Risk Management:**

Looking at the low sales numbers in the forecast helps us plan for tough times. This way, we can be prepared if sales drop or the market changes unexpectedly

## Conclusion

Looking at past sales data helps us predict what might happen in the future. This way, Home Depot can make better decisions about staffing, supplies, and advertising to keep growing and facing any bumps in the road.

## Future Work

Model Comparison: Compare the ETS model with other forecasting models such as **ARIMA, Prophet** etc.



