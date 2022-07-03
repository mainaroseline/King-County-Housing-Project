# Housing Dataset Analysis

## Introduction
In this project we are going to perform a linear Regression analysis that's covering both inferential modeling and predictive modeling. At the end of the analysis we are going to provide a final report on all of our findings.

## Business Understanding
Our client is a real estate agency situated in King County, Washington that helps homewoners buy / or sell homes. They are looking to get a better understanding on what features about a house are the most important when trying to estimate a homes price in that area so as to know how a shift in the features may affect the pricing of the houses.
 
 They also what you to come up with a pricing algorithm to give an estimate of a home's price based on different features to assist buyers and sellers evaluate their homes.

## Data Understanding
We have been provided access to data containing information on over 10,000 homes together with their respective features. The data used in the analysis contains information on the King County homes pricing together with the different features that make up the homes. The data is contained in the Data folder where:
 1. kc_house_data.csv contains data on the different houses together with their features
 2. column_names.md contains a breakdown on the Column Names and their descriptions for Kings County Data Set

The data modeling will be broken down in two parts where the first bit will focus on the inferential modeling and the second bit will be on predictive modeling.

## Load The Data
In this stage of the analysis, i imported the necessary libraries that will be used during the analysis and obatined the data into the notebook. Next, i checked at the different columns contained in the data aand familiarized myself with what is contained in the different columns using the 'column_names.md' data.

## Data Cleaning
After loading the data into the notebook and familiarizing myself with the data, i started working on cleaning the data. Here, i check the columns datatypes and assigned new data types to columns that were not assigned properly. Next i checked my data for null entries  and multicollinearity and also figured out ways to deal with the two. After cleaning the data next came the data exploration 

## Exploring The Data
After cleaning the data, I started exploring the data by ploting different distribution plots like histograms. Next, i checked the data for numerical and categorical variable and identified the columns that contained the respective variable types. For columns that were categorical and were assigned the numerical variable i assigned the correct variabled type. After this i did the one hot encoding to make it possible for me to use the categorical variables in creating the linear regression results,

## Modeling The Data
After exploring the data, i used the preprocessed data in creating the models.
First i started by creating the inferential models, i created two models here:
 1. One was based on the target('price') and the most correlated feature('sqft_living')
 2. The secong one was based on the target('price') anf the five most correlated features(sqft_living, bathrooms, grade_7, bedrooms, grade_10)
The next model i created was the predictive model, i also created two models here:
 1. linear  Regression Model
 2. Polynomial Regression Model

## Evaluation
After modeling the data, i did the model evaluation. Here i eveluated the models and gave a brief summary about the model finding and what certains values were communicating about the data. I also made recommendations on the two features that showed the strongest correlation with the price of a home and what it meants. The two features were 'sqft_living' and 'grade's
