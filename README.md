# Black-Friday-Sales-Prediction
![alt text](https://searchengineland.com/figz/wp-content/seloads/2014/12/black-friday1-ss-1920.jpg "Black Friday Sales Prediction")

## Table Of Contents
  - [Project Introduction](#project-introduction)
  - [Dataset Description](#dataset-description)
  - [EDA](#eda)
  - [Data Preprocessing](#data-preparation)
  - [Modeling Phase](#modeling-phase)
  - [Evaluation Metric](#evaluation-metric)
  - [Conclusion](#conclusion)

### Project Introduction
Black Friday is an informal name for the Friday following Thanksgiving Day in the United States, which is celebrated on the fourth Thursday of November. The day after Thanksgiving has been regarded as the beginning of the United States Christmas shopping season since 1952, although the term "Black Friday" did not become widely used until more recent decades. Many stores offer highly promoted sales on Black Friday and open very early, such as at midnight, or may even start their sales at some time on Thanksgiving. The major challenge for a Retail store or eCommerce business is to choose product price such that they get maximum profit at the end of the sales. Our project deals with determining the product prices based on the historical retail store sales data. After generating the predictions, our model will help the retail store to decide the price of the products to earn more profits.

### Dataset Description
The dataset is acquired from kaggle from the profile of . The data contained features like age, gender, marital status, categories of products purchased, city demographics, purchase amount etc. The data consists of 12 columns and 550068 records. Our model will be predicting the purchase amount of the products.

###  EDA:
  Data visualization for understanding the dataset better and finding the patterns.

### Data Preparation
* Used LabelEncoder for encoding the categorical columns .
* Filled the missing values.

### Modeling Phase
- Splitted dataset into into random train and test subset of ratio 80:20
- Implemented multiple supervised models such as Linear Regressor and Xg booster.

### Evaluation Metric
Root Mean Square Error (RMSE) , Train score and Test score was taken into consideration.

### Conclusion
XgBoost is the suggested model which can be used as it is fast and its capacity to do parallel computation on a single machine.
Also from the score comparison we can see that it is not overfitting or under fitting.
The error rate is also low in XgBoost model.

