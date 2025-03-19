# Website Performance Analysis

## Overview
This project analyzes website performance metrics using Google Analytics data. It processes hourly website traffic data, visualizes key performance indicators, and implements time series forecasting to predict future traffic patterns.

## Features
- Data cleaning and preprocessing of Google Analytics export data
- Time series analysis of user traffic and session metrics
- Engagement metrics visualization and correlation analysis
- Channel performance comparison
- Traffic forecasting using SARIMA (Seasonal AutoRegressive Integrated Moving Average) models

## Requirements
- Python 3.x
- Libraries:
  - pandas
  - matplotlib
  - statsmodels

## Setup and Usage
1. Export your Google Analytics data to a CSV file named `data-export.csv`
2. Place the CSV file in the appropriate directory
3. Run the script:
   ```
   python website_performance_analysis.py
   ```

## Analysis Components

### Traffic Analysis
- Visualizes users and sessions over time
- Aggregates data by hour to identify traffic patterns

### Engagement Analysis
- Tracks key engagement metrics:
  - Average engagement time per session
  - Engaged sessions per user
  - Events per session
  - Engagement rate

### Channel Performance
- Compares performance across different marketing channels
- Normalizes metrics for fair comparison

### Correlation Analysis
- Scatter plots to identify relationships between engagement metrics

### Time Series Forecasting
- ACF and PACF plots for time series model configuration
- SARIMA model implementation with 24-hour seasonal periodicity
- 24-hour traffic forecast

## Visualization Outputs
- Time series plots of traffic metrics
- Multi-panel visualization of engagement metrics
- Correlation scatter plots
- Channel performance bar charts
- ACF/PACF diagnostics
- Forecast visualization

## Future Improvements
- Interactive dashboards
- Real-time data integration
- Anomaly detection
- Multi-dimensional analysis with demographic data
