# LP2 - Favorita Store Sales - Time Series Forecast
*This is a time series forecasting problem. In this project,  ML model is built to predict store sales on data from Corporation Favorita, a large Ecuadorian-based grocery retailer.*

## Summary
| Code      | Name        | Published Article |  
|-----------|-------------|:-------------:|
| LP2       | Store sales - Time Series Forecast    |  [https://medium.com/@kobenaenyam/store-sales-analysis-and-forecast-d2554a62be40](/) | 
--------------------------------------------------

## Project Description
The project is divided in three stages: 
*	Initial Exploratory Data Analysis.
This stage proceeds after the business and data understanding phase. The merged data was checked for missing values. Depending on the nature of the values missing, the right approach is adopted to replace or do away with the missing values. Then, relevant questions are asked to understand the sales trends and business operation of Favorita.


* Time Series Analysis

In this stage, the sales trend with time was looked into. Insights were drawn to highlight the seasons of high  and low sales throughout the data. The impact of an earthquake that happened was also accessed using visualizzations in python. 

*	Time Series Forecasting -Summary 
The summary of the model is shown below:

| Model      | MSE       | RMSE|  RMSLE|
|-----------|-------------|:-------------:|------:|
| AR model      |  133,593,712,396.331| 365,504.740  |0.460|
|ARIMA model |   62,010,718,148.119    | 249,019.510        |   0.320   |     
|Linear Model|  0.690 |  0.830 |  0.270  |     
|Decision Tree|  0.070 |  0.260 | 0.060  |   
|XgBoost| 0.120 |0.350 | 0.120|  
|Random Forest Model|0.040 |0.200 | 0.050| 

  

## Author
Kbay
