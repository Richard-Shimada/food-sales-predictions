# Predicting sales of various store items using regression models 


**Author**: Richard Shimada

### Business problem:

What features of items and the stores they are sold in are most impactful in determining total sales volume? 

### Data:
Dataset can be found online [here](https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/). Some visual callouts on the data set:


![image](https://user-images.githubusercontent.com/110313483/191888643-2063745e-48d7-4744-a68a-f88e6e2415df.png)

Supermarkets have the highest total volume, with Type 1 stores having the majority of total sales volume (over $12M).


![image](https://user-images.githubusercontent.com/110313483/191889066-f91da510-d333-4c48-9078-c969c13c2100.png)

Within the actual items sold, all item types have a similar MRP in the $130 to $160 range.

## Pre-processing
To prepare the dataset for modeling, I removed duplicates, imputed unknown values, encoded categorial data, and scaled numerical data.


## Modeling

A Linear Regresssion and Regression Tree Model were both fit to the data. The Regression Tree model's max depth was tuned to improve the predictive power of the model.

## Results

Report on MAE/MSE/RMSE/R2

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

Use the regression tree, variance has been corrected and good predictive power.


## Limitations & Next Steps

To further improve results, instead of a Linear Regression model we could try a Ridge, Lasso, or Elastic Net model. In addition to the regression tree, we could also try implementing other tree models such as bagged trees and random forests.


### For further information

For any additional questions, please contact Richard Shimada at r.shimada@gmail.com.
