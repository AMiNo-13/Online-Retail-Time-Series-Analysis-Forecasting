## Online Retail Customer Segmentation & Sales Prediction

### Overview

Due to the pandemic, online sales became very crucial for businesses. In order to maintain their success, they have to make sure to attract and maintain their customers and also to be able to maintain their sales at the same time. Predicting sales and RFM analysis is one of the most important business problems for any retail entity. An RFM analysis can be used in conjunction with sales prediction models to gain even further insight into customer behavior. This also can help in directing the marketing efforts and managing its inventory in right direction to increase the chances of sale.
 

### Online Retail Business


The global online retail market size was valued at USD 4.25 trillion in 2019 and is expected to grow at a compound annual growth rate (CAGR) of 9.4% from 2020 to 2027. Increasing usage of smartphones and the convenience of purchasing daily essentials and luxury products from the comfort of home is primarily driving the growth. The internet has revolutionized the retail industry by increasing the reach of retailers from the local area to overseas, allowing the business to reach the expediency of customer and increasing the cross-broader success.  

### Our Data

This is a transnational dataset which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Most sales comes from UK and about 90% customers also are from UK, outside UK, most of the sales are from Europe.


### The Model and Results

<img width="938" alt="Screen Shot 2020-12-17 at 9 32 28 PM" src="https://user-images.githubusercontent.com/62824675/102610496-24da3980-40e2-11eb-9b69-8e86d86cc56e.png">

<img width="938" alt="Screen Shot 2020-12-17 at 9 35 07 PM" src="https://user-images.githubusercontent.com/62824675/102610640-64088a80-40e2-11eb-804c-2fa4790f30ab.png">

I splited the dataset into two categories, the first one s only UK based customers and second one is the International countries. We ran the dataset on three different models: Linear regression, Decision Tree Regressor, and Random Forest Regressor. Then I used GridSearchCV to find the optimal hyperparameters of a model which results in the most 'accurate' predictions. On the UK dataset I got 80% and on the second mdel I got was close to 65%. 


### Conclusions

This peformance represents a first step in sales prediction and analysis. There is still improvement can be done to improve our model, and much improvement is required before deployment; however, these results do suggest that our model is doing well and can be improved. Our RFM analysis can give a valuable insights for business direct marketing.

### The Future

The potential applications of this technology are only limited by quantity and quality of data. Some next steps for this dataset would be to:
-  **More data from different countries.** Since the data is mostly UK based, it would nice to get more data from its international customers to have better model.  
-  **More diverse data.** Since we created two datasets, we would like use these two datasets separately to have more standardized data for a model because there can be some patterns that work for other countries and do not for UK or vise versa.  
- **Data on other online retail businesses.** I would like to use my model on different online retail data to see how it would performs against other datasets. This way we can improve our model better 

