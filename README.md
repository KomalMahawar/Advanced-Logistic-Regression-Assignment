# Advanced Logistic Regression
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file added to the repository.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

Business Goal
We are required to model the price of houses with the available independent variables. It will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high rewards. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- What is the background of your project?
- The project was provided as an assignment by Upgrad team.
- What is the business probem that your project is trying to solve?
- We are required to model the price of houses with the available independent variables. It will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high rewards. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- What is the dataset that is being used?
- train.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We have built model and came to conclusion that Lasso provides the better model as compared to Ridge.
- Below are the R2 score of all the models: 

Metric	            Linear Regression	   Ridge Regression	    Lasso Regression
0	R2 Score (Train)	7.989130e-01	       7.933674e-01	        7.975042e-01
1	R2 Score (Test)	  8.006068e-01	       7.906959e-01	        7.951484e-01
2	RSS (Train)	      1.283308e+12	       1.318700e+12	        1.292299e+12
3	RSS (Test)	      5.634303e+11	       5.914360e+11	        5.788543e+11
4	MSE (Train)	      3.545297e+04	       3.593851e+04	        3.557694e+04
5	MSE (Test)	      3.582514e+04	       3.670469e+04	        3.631218e+04


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3
- sklearn
- matplotlib
- scipy.stats
- seaborn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad 
- Google,Data Science projects from Kaggle


## Contact
Created by [@KomalMahawar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
