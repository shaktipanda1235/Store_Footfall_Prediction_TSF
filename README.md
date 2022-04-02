# Inspiration
Beyond Machine Learning Models, Time Series Forecasting plays an integral role for bussiness depending upon outlets and sales. So I tried an approch of solving a most 
common day to day customer visits to outlets, whose prediction can be bettered using both Linear Regression and Time Series Forecasting.

# Explratory Data Analysis
* About 20-25% of the values are zero for customers which may be an indication of store closure for that day.
* Impact of the promotion is clearly visible in the grouped boxplots below even across month. However for December, no impact of promotion is visible.
  ![image](https://user-images.githubusercontent.com/102746816/161394662-05df7d9a-e457-4c93-82a8-ea45504016ee.png)
* Customer count was high when there is a state holiday.
  ![image](https://user-images.githubusercontent.com/102746816/161394696-aa64d35f-c447-4e76-aae7-ff99434f3553.png)
# Model Building
* Dickey-Fulher tests suggested stationarity of time-series.
* Various models are built with and without considering seasonality and a **SARIMAX model with Time Varying Linear Model** performed the best according to rmse values.


  ![image](https://user-images.githubusercontent.com/102746816/161394842-9b183e75-1938-40b8-8c0a-004374b2ff85.png)
