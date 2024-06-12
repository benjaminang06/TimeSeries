# Time Series Analysis and Forecasting using ARMA Models: A Case Study of the Philippine Stock Exchange

## Description

This project focuses on the application of time series analysis and forecasting techniques to predict future trends in the Philippine Stock Exchange Composite Index (PSEi). Using historical data spanning from February 1987 to April 2022, various ARMA models were tested to identify the most accurate predictor for the PSEi.

## Key Features

- **Data Collection**: Historical monthly closing prices of the PSEi were gathered from Yahoo Finance.
- **Data Preprocessing**: Log transformation and differencing were applied to ensure stationarity of the time series data.
- **Modeling**: AR(1), MA(1), and ARMA(1,1) models were evaluated using AIC values to determine the best fit.
- **Forecasting**: The AR(1) model, identified as the best fit, was used to forecast PSEi values with a high degree of accuracy (MAPE = 6.62%).
- **Visualization**: Detailed visualizations of the time series data and forecast results were created using RStudio.

## Results

The AR(1) model provided the most accurate forecasts for the PSEi, with a MAPE of 6.62%. The model's predictions suggest a steady increase in the PSEi over the following years, offering valuable insights for investors and policymakers.

## Repository Contents

- **Data**: The historical dataset used for analysis.
- **Code**: R scripts for data preprocessing, modeling, and forecasting.
- **Results**: Visualizations and analysis of the model's performance.

## Getting Started

To explore the analysis and results, clone this repository and run the R scripts provided in the `/code` directory. Detailed instructions and dependencies are listed in the `README.md` file.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/benjaminang06/Time-Series-Analysis
    cd Time-Series-Analysis
    ```

2. Install the required R packages:
    ```R
    install.packages(c("TSA", "tseries", "lmtest", "tidyverse", "forecast", "quantmod", "ggplot2", "xts"))
    ```

## Usage

Run the R scripts to preprocess data, fit the ARMA models, and generate forecasts:
```R
source('code/preprocess_data.R')
source('code/fit_models.R')
source('code/forecast.R')
```

## Authors

- Benjamin Louis Ang
- Brynx Junil Alegarbes
- Jeremy Marcus Tan


