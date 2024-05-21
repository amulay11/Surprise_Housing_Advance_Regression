# Project Name
> Regression model building using regularization for Surprise Housing company in order to predict the actual value of the prospective properties and decide whether to invest in them or not. 


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Key Steps](#key-steps)
* [Technologies Used](#technologies-used)




## General Information
- Project Backround:
    A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
- Business Problem to solve:
    The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. 
    The company wants to know:
        Which variables are significant in predicting the price of a house, and
        How well those variables describe the price of a house.
- Dataset being used:
    A data set has been provided in a csv format with 81 features and 1460 samples. An elaborate data disctionary has also been provided to describe the predictor features in the dataset


## Conclusions
- Base model with linear regression is able to explain 84% of the variance in the training data. However it gives a low performance on the test data indicating an overfit on the train data.
- In order to genralize the model, Ridge and Lasso based models were tried with different values of hyperparamaters.
- The Ridge based model with optimal value of hyperparameter provided a better performance overall on the test data. Thus this model has been chosen.
- Top 6 most significant features that help to predict the price of the house are as follows (listed with most significant at the top):
    - OverallQual  - Rates the overall material and finish of the house
    - GrLivArea    - Above ground living area in square feet
    - GarageCars   - Size of garage in car capacity
    - TotRmsAbvGrd - Total rooms above ground (not including bathrooms)
    - ExterQual    - Evaluates the quality of the material on the exterior
    - KitchenQual  - Kitchen quality
- The model is able to describe 82.65% of the variance on the test data.  

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Key steps
- 1. Data understanding and handling of quality issues
- 2. Data Handling & Encoding
- 3. Data analysis and visualization
- 4. Model building, evaluation & apply regularization
- 5. Selection of the best model

## Technologies Used
- sklearn
- statsmodel
- Ridge & Lasso regularization
- Cross validation

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@amulay11] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->