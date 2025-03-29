# Avocado Prices Analysis and Prediction

This project focuses on analyzing avocado prices across different regions in the United States and predicting future trends using time series models. The analysis includes exploratory data analysis (EDA), feature engineering, and model training for forecasting.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Analysis](#analysis)
- [Models](#models)
- [Results](#results)

## Introduction
Avocados are a popular fruit in the United States, and their prices vary significantly across regions and time. This project aims to:
- Analyze historical avocado price trends.
- Explore regional differences in prices, volumes, and revenues.
- Build predictive models to forecast future prices.

## Dataset
The dataset contains information about avocado prices, sales volumes, and other features across various regions in the United States. Key columns include:
- `Date`: The date of the observation.
- `AveragePrice`: The average price of a single avocado.
- `Total Volume`: The total number of avocados sold.
- `Region`: The region where the data was collected.
- `Type`: The type of avocado (conventional or organic).

## Features
The analysis includes:
- **Regional Analysis**: Comparing prices and volumes across regions.
- **Time Series Analysis**: Decomposing and analyzing trends, seasonality, and residuals.
- **Choropleth Maps**: Visualizing regional price differences on a map.

## Analysis
Key steps in the analysis:
1. Data preprocessing and cleaning.
2. Exploratory Data Analysis (EDA) to uncover trends and patterns.
3. Visualization of regional and temporal price variations.
4. Feature engineering for model training.

## Models
The project uses the following models for forecasting:
- **ARIMA**: Autoregressive Integrated Moving Average.
- **SARIMA**: Seasonal ARIMA for capturing seasonality in the data.

## Results
- Regional differences in avocado prices were identified, with California having the highest average prices.
- Time series models provided accurate forecasts for short-term price trends.
