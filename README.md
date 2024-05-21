##### prophet-challenge
## Sources
I had used Chat CPT, and GITHub open source matterials to compplete this assignment. I have used Kalvin Anglin repository as an example to complete this assignment - randomely located on github repository.  
##Overview
Project requires to produce growth analyst at Mercado Libre of analyzing the company's financials and search trends to determine if there is a way to predict how to make the company grow. 
## Purpose 
To determine the accuracy of a Prophet Time Series Model in predicting future growth for MercadoLibre, we compared the model's predictions to data exploration focused on identifying patterns in hourly Google search traffic. This involved analyzing correlations between search traffic and seasonality, and relating search traffic to stock price patterns.
##Outcome
1. Total search traffic for May increased compared to the monthly median across all months, coinciding with MercadoLibre's financial results release.
2. Search trends rise around 9 AM, with Monday and Tuesday being the busiest days, and notable increases in trends before holiday weeks.
3. By combining stock and search trends data for the first half of 2020, it was confirmed that new customers and revenue increased after the March 2020 market shock. A spike in search trends and stock price in early May indicates increased search activity in anticipation of quarterly financial results.
4. Introducing a "Lagged Search Trends" column showed a better correlation between search trends and the following week's stock prices.
5. Calculating the standard deviation of the closing stock price over a 4-hour rolling window revealed that high volatility in early 2020 was typical, with high volatility days often followed by more high volatility days.
6. The correlation matrix indicated a slight negative correlation between search trends and stock volatility, and a very small positive correlation between search trends and hourly stock returns, though the latter was too close to zero for definitive predictions. Such insignificant correlations indicate that there is practically no relationship between measured items. 
A time series model to forecast MercadoLibre's near-term popularity based on hours was challenging. The model performed better with daily data, showing a dip in search traffic over an 80-day period. Forecast components confirmed peak popularity on Tuesdays from 10 AM to 1 PM and 10 PM to midnight. The lowest search traffic was in mid-October.

## Github link
https://github.com/GrigoriyIsayev/prophet-challenge
