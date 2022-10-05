# Project Name
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
> The company wants to know:1) Which variables are important to predict the Sale price of the house. 2) How well these variables describe the price of the house.


## Table of Contents
* General Information 
* Technologies Used: Python-statisticsModel and sklearn 
* Conclusions
* Acknowledgements


## General Information
- We have created a Regression model using Ridge and Lasso to predict the Sale price of the houses using various independent variables.
- We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- The dataset train.csv is given to us for this assignment. It has 1460 records and 81 features. There is 43 object type, 3 float and 35 int type features. There are 19 variables which has missing values in the dataset.I have handled missing values in this assignment. 


## Conclusions
- The ridge regression with hyperparameter lambda value as 2 and the Lasso regression with hyperparameter lambda value as 0.0001 produces optimal results. 
- For both Ridge and Lasso GrLivArea , 1stFlrSF , OverallQual_9, YearBuilt, OverallQual_10. 
- Both the regression has aboave 85% R2 score.


## Technologies Used
- Python 3.8.5



## Acknowledgements
- This Project is a part of Upgrad advance ML assignment
- The github link to this project is git@github.com:seemasim/House-Price-Prediction.git


## Contact
Created by [@seemasim] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->