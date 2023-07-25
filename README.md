# Advanced Logistic Regression
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file added to the repository.
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

- Linear Regression	   
-	R2 Score (Train) : 7.98       
-	R2 Score (Test)  : 8.00   

- Ridge Regression
-	R2 Score (Train) : 7.93   
-	R2 Score (Test)  : 7.90
  
- Lasso Regression 
-	R2 Score (Train) : 7.97      
-	R2 Score (Test)  : 7.95      
The features which would vary the housing prices are ;
OverallQual, 1stFlrSF, 2ndFlrSF, MSSubClass_90,	MSSubClass_120,	MSSubClass_160,	MSZoning_RL,	LotConfig_CulDSac,	Neighborhood_Crawfor,	Neighborhood_NoRidge , Neighborhood_NridgHt,	Neighborhood_Somerst,	Neighborhood_StoneBr,	Neighborhood_Veenker,	HouseStyle_2.5Unf,	Exterior1st_Stucco,	Exterior2nd_ImStucc,	Exterior2nd_VinylSd	 


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
* IDE - Anaconda Jupyter Notebook and VS Code
* language - python v3.9
* library - pandas v1.4.4
* library - numpy v1.21.5
* library - matplotlib v3.5.2
* library - seaborn v0.11.2
* library - sklearn
* library - statsmodel


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad 
 * References:
* https://stackoverflow.com/
* https://www.kaggle.com/
* https://www.google.com/
* https://towardsdatascience.com/

## Contact
Created by [https://github.com/KomalMahawar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
