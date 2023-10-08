# Time Series Analysis in Restaurant Orders Data Science Project

## Input Data

- **TimeSeries**: Daily order counts from five randomly selected restaurants. Data may contain missing dates and anomalous values. Series starts from each restaurant's opening date.
  
- **Calendar**: Calendar data for 2016-2024 with an `is_holiday` flag marking official holidays separate from weekends.

## Objectives

1. **Data Cleaning**: Remove outliers and data anomalies.

2. **Time Series Decomposition**: Break down time series into components:
    - Trend
    - Weekly Seasonality
    - Noise

3. **Forecasting**: 
    - Use Prophet for forecast up to December 31, 2024.

4. **Visualization**: 
    - Highlight anomalous data points and their corrected values.
    - Each time series component should have its own plot.
    - Plot time series and forecasts.

## Known Anomalous Periods
- **March 30, 2020 & July 31, 2020**: General COVID-19 lockdown.
- **June 12, 2021 & July 31, 2021**: Public place restrictions in Moscow (QR-code only).
- **October 26, 2021 & November 12, 2021**: Moscow lockdown due to COVID-19 surge.