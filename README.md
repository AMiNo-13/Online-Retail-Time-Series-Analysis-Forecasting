## Online Retail Time Series Analysis & Forecasting

### Overview

Due to the pandemic, online sales became very crucial for businesses. One of the tools to maintain their success is to use time series analysis. A major benefit of time series analysis is that it can be the basis to forecast data. This is because time series analysis — by its very nature — uncovers patterns in data, which can then be used to predict future data points. In my research I used ARIMA (AutoRegressive Integrated Moving-Average time-series) analysis to create daily and weekly forecasting models for the top 10 products and total sales.
 

### Online Retail Business

The world of online sales is becoming increasingly complex as more and more people begin to buy and sell goods online. The global online retail market size was valued at USD 4.25 trillion in 2019 and is expected to grow at a compound annual growth rate (CAGR) of 9.4% from 2020 to 2027. Increasing usage of smartphones and the convenience of purchasing daily essentials and luxury products from the comfort of home is primarily driving the growth. The internet has revolutionized the retail industry by increasing the reach of retailers from the local area to overseas, allowing the business to reach the expediency of customer and increasing the cross-broader success.

### Our Data

<img width="967" alt="Screen Shot 2020-12-17 at 11 18 31 PM" src="https://user-images.githubusercontent.com/62824675/102611224-628b9200-40e3-11eb-80b8-496843bc9b3e.png">

<img width="430" alt="Screen Shot 2021-01-04 at 4 25 31 AM" src="https://user-images.githubusercontent.com/62824675/103538835-d8199100-4e4b-11eb-943f-bce8c81add57.png">

This is a transnational dataset which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Most sales comes from UK and about 90% customers also are from UK, outside UK, most of the sales are from Europe. In my research I analyzed and studied this dataset and used time series analysis to build a model using ARIMA for the top products and total sales to find the best model that can help and guide the company future decisions.


### The Model and Results

<img width="430" alt="Screen Shot 2021-01-03 at 10 26 02 PM" src="https://user-images.githubusercontent.com/62824675/103538764-b3bdb480-4e4b-11eb-847b-30158bea385b.png">



For my time series analysis and modling I used ARIMA statistical model. ARIMA model provides a simple yet powerful method for making skillful time series forecasts.
The line plot is showing the observed values compared to the rolling forecast predictions. Overall, the forecasts align with the true values very well showing an upward trend in sales. I have also forecasted top ten products weekly and daily sales in my analysis that can be found in my notebook. Based on products forecasts models we suggested that to have enough inventories for Products#: 2, 4, 5, 8, and 10 since the trend for those products are upwards. 


### Conclusions

Creating a time series model allowed us to make adjustments to different measurements, tuning the model to make it potentially more accurate. The models showed that the forecasted values catch up to the observed values in the dataset which is really good. Obviously there are still room for improvements, the models were the first step in sales forecasts and analysis. The product models forecast can be helpful tool the inventory management for determining which products trend is upward or downward. 

### The Future

The potential applications of this technology are only limited by quantity and quality of data. Some next steps for this dataset would be to:
-  **More data.** Since the data is mostly UK based, it would nice to get more data from its international customers to see if our model would change especially for the top products. As we saw in our dataset there was an upward trend in the business, that means some products might start selling more than the others in feature.
-  **Update Automation.** As products and technology updates our models needs to update and improve too. For my future analysis I would to see if we can introduce model that would automatically updates based on the sales and new products. 
-  **More diverse methods.** There are many ways or methods that we can do time series analysis. I would like to try different methods to see if it would improve our forecasts and models.
- **Data on other online retail businesses.** I would like to use my model on different online retail data to see how it would performs against other datasets. This may help to improve our model. 
