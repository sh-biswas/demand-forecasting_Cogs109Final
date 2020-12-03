# Demand-Forecasting

## A description of your dataset

This dataset contains 8 attributes and 28764 instances. The data consists of multiple fulfillment centers with meal demands


## How will you explore and visualize your data? 

 - For each store, we can visualize how many of each item they bought over the full time period give
 - Number of sales made for each store in a histogram
 - Which stores bought more of what items around what times


## Your group's research question
 - What are the meals/supplies demands for each fulfillment center for the next month?


## Your planned analysis
 - Multivariate regression with all predictors, group by time in order to determine what is seasonal
 - K-fold validation (good cross-validation technique)
 - We can try to predict sales that will increase in the next month using the seasonal sale data and using higher order linear regression models


## Your planned report 
 - Plot graphs of k-fold validation
 - EDA
 - Graph multivariate regressions
 - Predictions of sales per center
