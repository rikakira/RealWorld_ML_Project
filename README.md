# RealWorld_ML_Project

We are building this project for a virtual real estate company(let's name it Ritika Real Estate) whose main aim is to improve their house price predictions and in result increase their sales. I have mentioned the problem statement, questions you must ask before working on this project and all the important literary information below.

**Problem Statement-**
We are given a dataset of house prices with some features like number of bathrooms, number of bedrooms, etc. Our task is to create a model which will predict the house price by looking at it's features.

**Questions-**
1. What is the business objective and end goal? How will Ritika Real Estate benefit from it?
Ans. The company will predict the prices of the real estates in a given area and invest in that area if it's undervalued.
2. How does the current solution look like? i.e. how can we work on this?
Ans. Till now manual experts have been working on price prediction and it has reported an error of nearly 25% which has caused a lot of losses. This is why we are relying on ML.

**Before starting-**
This is a supervised learning model because we have features and labels. 
This is a regression task as it calculates  a value and since here we need the value, i.e. price.
This is a batch learning technique as we already have the data.

**Things we need to calculate-**
1. Selecting a performance measure.
   A typical performance measure is for regression problems is root mean square(RMSE). We shall be choosing RMSE only. Other performance measures include Mean Absolute Error, Manhattan Norm. etc.
2. Checking the assumptions.
   We need to make sure that the price is needed and not the categories like expensive, cheap, etc.
 
**Attributes/Features for House Price Prediction**
We shall be using thirteen continous attributes and one binary-valued attribute.
    1. CRIM      per capita crime rate by town
    2. ZN        proportion of residential land zoned for lots over 
                 25,000 sq.ft.
    3. INDUS     proportion of non-retail business acres per town
    4. CHAS      Charles River dummy variable (= 1 if tract bounds 
                 river; 0 otherwise)
    5. NOX       nitric oxides concentration (parts per 10 million)
    6. RM        average number of rooms per dwelling
    7. AGE       proportion of owner-occupied units built prior to 1940
    8. DIS       weighted distances to five Boston employment centres
    9. RAD       index of accessibility to radial highways
    10. TAX      full-value property-tax rate per $10,000
    11. PTRATIO  pupil-teacher ratio by town
    12. B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks 
                 by town
    13. LSTAT    % lower status of the population
    14. MEDV     Median value of owner-occupied homes in $1000's
    
    
