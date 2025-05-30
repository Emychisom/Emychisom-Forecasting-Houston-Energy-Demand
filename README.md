# ERCOT Load Forecasting Project

## Project Overview
This project focuses on forecasting electricity load in the ERCOT region using historical load and weather data. The goal is to build accurate predictive models and deploy an interactive dashboard for visualization.

## Data Sources
- **ERCOT Load Data:** Hourly load data from ERCOT.
- **Weather Data:** Temperature observations from Houston International Airport and Dallas/Fort Worth.

## Data Preprocessing
- Missing values handled via interpolation and forward/backward filling.
- Timestamp columns converted to datetime format and set as index.
- Relevant features selected for modeling.

## Forecasting Model
- Model used: Prophet (time series forecasting model by Facebook).
- Model trained on historical load data to predict future load values.
- Model evaluation metrics: RMSE, MAE (include actual values if available).

## Running the Streamlit App
1. Clone this repository.
2. Install dependencies:
