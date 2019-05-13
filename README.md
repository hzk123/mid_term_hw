# Future-Sales-Prediction-using-Machine-Leanring
####  Predict Future Sale  Kaggle competition: https://www.kaggle.com/c/competitive-data-science-predict-future-sales


![](https://d25qe19fo1nsn4.cloudfront.net/wp-content/uploads/2016/12/how-to-do-a-competitive-analysis-blog-header-1024x386.jpg)

In this competition you will work with a challenging time-series dataset consisting of daily sales data, kindly provided by one of the largest Russian software firms - 1C Company. 

We are asking you to predict total sales for every product and store in the next month. By solving this competition you will be able to apply and enhance your data science skills.

### Dataset:
You are provided with daily historical sales data. The task is to forecast the total amount of products sold in every shop for the test set. Note that the list of shops and products slightly changes every month. Creating a robust model that can handle such situations is part of the challenge.

**Train and Test Data**: https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data

#### Data fields
- ID - an Id that represents a (Shop, Item) tuple within the test set
- shop_id - unique identifier of a shop
- item_id - unique identifier of a product
- item_category_id - unique identifier of item category
- item_cnt_day - number of products sold. You are predicting a monthly amount of this measure
- item_price - current price of an item
- date - date in format dd/mm/yyyy
- date_block_num - a consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33
- item_name - name of item
- shop_name - name of shop
- item_category_name - name of item category
# mid_term_hw methods

- First of all , use the experience of [*Two Sigma: Using News to Predict Stock Movements*](https://www.kaggle.com/c/two-sigma-financial-news) , the most important feature in price prediction competition is time lag
- [Stage 0](https://www.kaggle.com/dhimananubhav/feature-engineering-xgboost)Try a little about public kernel <<Feature engineering, xgboost>> , it seems very hard to improve.
- [Stage 1](https://gist.github.com/hzk123/33ac902233e3c36fa96d9da3a07ca065) Try to improve this method, use much more time lag data and ensemble many methods , but it seems Xgboost is best for this work, or for private leaderboard.
- [Stage 2](https://nbviewer.jupyter.org/gist/hzk123/b8e816a8db27e28e86cbc1fe59032220) , find a clean kernel , and try to improve and modify it , and get 0.885 in pb
- [Stage 3](https://nbviewer.jupyter.org/gist/hzk123/ab6b350b29b5087040d7f6771e3102fc), simple Ensemble , try to combine these methods , but result not good.


# Get
