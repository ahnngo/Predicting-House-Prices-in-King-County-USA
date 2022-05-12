# Predicting Housing Prices: Project Overview 
* Created a model that estimates housing price (Variance Score = 0.8) to help predict housing prices in King County based on house's features
* Implemented Feature Engineer to punish outliers, decreasing MSE by $20k and MAE by $3k using a deep learning model
* Improved Variance Score by 0.1, from 0.7 (Linear Regression model) to 0.8 by deploying a neural network with two hidden layers

## Code and Resources Used 
**Python Version:** 3.10
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn
**Dataset:** https://www.kaggle.com/datasets/harlfoxem/housesalesprediction  

## EDA
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the pivot tables. 

![alt text](https://github.com/ahnngo/Predicting-House-Prices-in-King-County-USA/blob/master/price_distribution.png)
![alt text](https://github.com/ahnngo/Predicting-House-Prices-in-King-County-USA/blob/master/geographical.png)
![alt text](https://github.com/ahnngo/Predicting-House-Prices-in-King-County-USA/blob/master/price_sqftliving.png)

## Model Building 

First, I deployed Linear Regression Model and Neural Network and compared to see which model yield better predictions. As described in the overview, the deep learning model was able to make better prediction of a variance score of 0.8
![alt text](https://github.com/ahnngo/Predicting-House-Prices-in-King-County-USA/blob/master/losses.png)
![alt text](https://github.com/ahnngo/Predicting-House-Prices-in-King-County-USA/blob/master/y_test_predictions.png)

## Model performance
* MAE: 148387.26762949396
* MSE: 99239.01488880099

