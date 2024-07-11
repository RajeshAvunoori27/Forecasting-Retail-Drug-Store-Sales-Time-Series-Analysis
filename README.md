# Retail-Store-Sales-Prediction

## Project Overview
This project aims to forecast daily sales for a retail company. Accurate sales predictions are crucial for optimizing inventory management, staffing levels, and promotional strategies. The forecasting process involves various time series analysis methods to provide store managers with timely insights for proactive decision-making and operational efficiency.

## Problem Statement
The retailer faces challenges in predicting daily sales, which are influenced by multiple factors such as promotions, competition dynamics, holidays, seasonal fluctuations, and local market conditions. Effective forecasting models are essential for empowering store managers to make informed decisions. Currently for simplicity in this project forecasted sales for each store seperately

## Data
The dataset includes the following columns:
- Store: Unique ID for each store
- DayOfWeek: Day of the week
- Date: Date of the data
- Sales: Turnover for any given day (target variable)
- Customers: Number of customers on a given day
- Open: Indicator if the store was open (0 = closed, 1 = open)
- Promo: Indicator if the store was running a promo
- StateHoliday: Indicator of a state holiday
- SchoolHoliday: Indicator if the date was affected by the closure of public schools

## Prediction Horizon
In this project we are able to forecast sales up to 27 weeks (189 days) in advance, allowing store managers to plan inventory, staffing, and promotional activities effectively.

## Methodology
We have used different methodologies for forecasting the sales. The methods used are listed below
**Univariate Methods**
- Average method
- Naive method
- Drift method
- Seasonal Naive method
- Simple Exponential Smoothing (SES)
- Holt’s Linear Trend method
- Theta Method
**Multivariate Methods**
- ARIMA (Auto Regressive Integrated Moving Average)
- SARIMA (Seasonal ARIMA)
- Prophet model (by Facebook)
- ARIMAX (ARIMA with exogenous variables)

## Project Workflow
- Data Collection
- Data Preprocessing
- Exploratory Data Analysis
- Model Building
- Model Evaluation
- Model Forecast
- Visualization

## Results
The models' results has been evaluated based on their accuracy in forecasting sales, with visualizations to illustrate the performance of each model. Among all the models the Prophet using multivariate is giving better results and it can be used in forecasting for all the stores



