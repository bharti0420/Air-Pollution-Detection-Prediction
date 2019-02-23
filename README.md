# Air Pollution Detection and Prediction

## Problem:
Detection of air pollution of such area for which we do not have data (like PM2.5, PM10, SO2, NO2, CO, O3). Sometimes we aren't able to collect air pollution data of some regions, but we need data from those regions for research purposes.

## Methods and Data Sources:
The research area is on Delhi, India. In the first stage, we analyze the spatial and temporal characteristics of air pollution of the 5 cities while in the second stage the Granger causality test is applied to investigate whether air pollution of a city is affected by its neighbors, and vice versa.

* For now we have used PM2.5 feature for this analysis.
One aim of this study is to test for causal relationships between air pollution of Delhi and its neighboring cities
by means of a time-series econometric method, specifically, Granger causality test. However, the first step is to
test if all AQI values are stationary and integrated of the same order. Hence, a unit root test, namely, augmented
Dickey Fuller (ADF) test is first introduced, followed by Granger causality test.

## Technology:
* Python
* Data Analysis
* Machine Learning
* Jupyter Notebook
