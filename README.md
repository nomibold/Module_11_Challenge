# Module_11_Challenge

This was done in Google Colab 

Step 1: Find unusual patterns in hourly Google search traffic
Read the data into the DataFrame and sliced the Data to May 2020
Used hbPlot to visualise the results
Calculated the total search traffic for the month and then compared the values to the monthly median across all months.

Step 2: Mine the search traffic data for seasonality
Grouped the hourly search data to plot the average traffic by the day of the week. 
Used hvPlot to visualize the traffic as a heatmap.
Grouped the data by the week of the year.

Step 3: Relate the search traffic to stock price patterns
Read the stock price data and concatenated it with to the search data in a single DataFrame. 
Sliced the data to 2020-01 to 2020-06 to check for common trends.
Created new columns: 
      “Stock Volatility”, which holds an exponentially weighted four-hour rolling average of the company’s stock volatility.
       “Hourly Stock Return”, which holds the percent change of the company's stock price on an hourly basis
Reviewed the time series correlation. 


Step 4: Create a time series model with Prophet
Set up a google search data for a prophet forecasting model. 
Plotted the forecast
Plot the individual time series components 

Step 5 (optional): Forecast revenue by using time series models
This is to forecast the total sales for the next quarter
Read the daily historical sales and then applied the Prophet model to the data
Produced a sales forecast for the finance group by giving them a number for the expected total sales in the next quarter. 
