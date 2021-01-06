## Online Retail Time Series Analysis & Forecasting

### Overview

Due to the pandemic, online sales became very crucial for businesses. One of the tools to maintain their success is to use time series analysis. A major benefit of time series analysis is that it can be the basis to forecast data. This is because time series analysis — by its very nature — uncovers patterns in data, which can then be used to predict future data points. 

Our data is from UCI Machine Learning Repository website. Link: http://archive.ics.uci.edu/ml/datasets/online+retail#. 
The client in this case is a UK-based and registered non-store online retail. The data contains about 540,000 observations domestic and internationally, and the company mainly sells unique all-occasion gifts. In my research I used ARIMA (AutoRegressive Integrated Moving-Average time-series) statistical model to create daily and weekly forecasting models for the top 10 products and total sales.
 

### Online Retail Business

The world of online sales is becoming increasingly complex as more and more people begin to buy and sell goods online. The global online retail market size was valued at USD 4.25 trillion in 2019 and is expected to grow at a compound annual growth rate (CAGR) of 9.4% from 2020 to 2027. Increasing usage of smartphones and the convenience of purchasing daily essentials and luxury products from the comfort of home is primarily driving the growth. The internet has revolutionized the retail industry by increasing the reach of retailers from the local area to overseas, allowing the business to reach the expediency of customer and increasing the cross-broader success.

In my research, my models forecasting can help overall business sales and inventory management. It can improve business financial decision making and management overall. For example, generally an ideal inventory management is when you have precisely the right amount of stock at all times. Too little, and you risk disappointing customers. Too much, and your inventory and warehousing costs can spiral. Warehouse space isn’t cheap, so it must better to use it as efficiently as possible. That's why forecasting is important and how my models can help. Right amount of stock can save space cost in warehouses and investment cost on each products. Not only it can help the inventory management system but also forecasting the total weekly and daily sales.

### Our Data

<img width="917" alt="Screen Shot 2021-01-04 at 4 50 08 AM" src="https://user-images.githubusercontent.com/62824675/103720559-79096880-4f80-11eb-92ac-f2da105b12f2.png">

This dataset which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Most sales comes from UK and about 90% customers also are from UK, outside UK, most of the sales are from Europe. In my research I analyzed and studied this dataset and used time series analysis to build a model using ARIMA for the top products and total sales. The modeles can help and guide the company to a better future decisions.


### The Model and Results

For my time series analysis and modling I used ARIMA statistical model. ARIMA model provides a simple yet powerful method for making skillful time series forecasts.

Here I am going to show my weekly trend and forecast graph:


<img width="438" alt="Screen Shot 2021-01-05 at 1 29 21 PM" src="https://user-images.githubusercontent.com/62824675/103725347-3600c280-4f8b-11eb-956d-5ed65d4c14fa.png">


By the graph you can see a upward trend in sales and high peack sales before holidays. My forecast is closely align with the true values which is good, showing an overall increase trend after a small decrease, but there still is room improvement. 

From the dataset I analyzed and forecast weekly and daily the top 10 products. Since they are close to 40 graphs in this research I am just going to go over few. You can see the entire model and graphs in my notebook. Here is the link: 

Here is one of the top product daily forecast:

<img width="433" alt="Screen Shot 2021-01-04 at 6 20 00 AM" src="https://user-images.githubusercontent.com/62824675/103544519-149dba80-4e55-11eb-9947-3d96bb69a911.png">

Overall, my forecasts closely aligns with the sales trend very well, showing an overall increase trend. Many of those high picks are related to holidays, but overall there is a lot of daily activity during May, June, July. Since it is a lunch bag this can be a indication that customers buy those not only for holidays gifts but mostly close to summer time since they can be used for outdoor activity. The forecast indicates that the manager or owner should invest more in this product and have it in stock since there is demand for it.

Let's check another forecast on a top product:

<img width="503" alt="Screen Shot 2021-01-05 at 4 36 42 PM" src="https://user-images.githubusercontent.com/62824675/103725364-3ef19400-4f8b-11eb-87c9-ea48bf7c4049.png">

Again as you can see my forecast aligns with the product trend very well, but there is downward trend towards October. However this product is more profitable than the previous product as you see on the total sales especially at those high peak days. The top peak 2 sales can be related to valentines day and eastern or Ascension day in the beginning in May. This easily can tell the managers or owners to have enough inventory on those peak days but as not as much towards the end of the year since there downward forecast trend. 


### Conclusions

Creating a time series model allowed us to make adjustments to different measurements, tuning the model to make it potentially more accurate. The models showed that the forecasted values catch up to the observed values in the dataset which is really good. Obviously there are still room for improvements, the models were the first step in sales forecasts and analysis. The product models forecast can be helpful tool the inventory management for determining which products trend is upward or downward. 

### The Future

Some next steps for this dataset would be to:
-  **More data.** Since the data is mostly UK based, it would nice to get more data from its international customers to see if my model would change especially for the top products. As we saw in our dataset there was an upward trend in the business, that means some products might start selling more than the others in feature.
-  **Update Automation.** As products and technology updates my models needs to update and improve too. For my future analysis I would to see if I can introduce model that would automatically updates based on the sales and new products. 
-  **More diverse methods.** There are many ways or methods that we can do time series analysis. I would like to try different methods to see if it would improve our forecasts and models.
- **Data on other online retail businesses.** I would like to use my model on different online retail data to see how it would performs against other datasets. This may help to improve my model. 
