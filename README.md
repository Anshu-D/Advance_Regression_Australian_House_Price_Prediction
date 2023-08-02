# Advanced House Price Regression
Predicting house prices using advanced regression techniques such as Ridge and Lasso.

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the 'test.csv' file uploaded in the repository.

The company is looking at prospective properties to buy to enter the market. This repository builds a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
-Which variables are significant in predicting the price of a house?
-How well those variables describe the price of a house?

Using GridSearchCV the model arrives at a final optimum lambda to determine the house prices using ridge and lasso regression.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Analysing the Sales Price of the Australian House Market
- The dataset is provided the information about the House Price for some certain period of time
- building a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:
-- Which variables are significant in predicting the price of a house, and
-- How well those variables describe the price of a house.


## Conclusions
- Suggestions for Surprise Housing is to keep a check on these predictors affecting the price of the house.
  The higher values of positive coefiecients suggest a high sale value.
  Some of those features are:-

 GrLivArea	  (Above grade (ground) living area square feet),
 OverallQual	(Rates the overall material and finish of the house),
 OverallCond	(Rates the overall condition of the house),
 TotalBsmtSF	(Total square feet of basement area),
 GarageArea	  (Size of garage in square feet)

- The higher values of negative coeeficients suggest a decrease in sale value.
  Some of those features are:-
  PropAge	(Age of the property at the time of selling),
  MSSubClass	(Identifies the type of dwelling involved in the sale)

- When the market value of the property is lower than the Predicted Sale Price, its the time to buy.¶
 


## Technologies Used
- pandas
- python
- numpy 
- sklearn 
- matplotlib
- seaborn
  

## Contact
Created by [@Anshu-D](https://github.com/Anshu-D)- feel free to contact me!


