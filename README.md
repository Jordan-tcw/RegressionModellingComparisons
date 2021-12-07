# RegressionModellingComparisons
This Google Colab file includes Python code to run and compare the accuracy of 7 regression models.
1. Linear regression
2. Forward and backward selection
3. Ridge regression
4. Lasso
5. Elastic net
6. PCR
7. PLS

Data used Carseats.csv = https://raw.githubusercontent.com/selva86/datasets/master/Carseats.csv

We will be trying to predict the sales of carseats.  In this data set, a single observation represents a location where carseats are sold.  In particular the training data set consists of the following variables:
Sales - Unit sales (in thousands) at each location
CompPrice - Price charged by competitor at each location
Income - Community income level (in thousands of dollars)
Advertising - Local advertising budget for company at each location (in    thousands of dollars)
Population - Population size in region (in thousands)
Price - Price company charges for car seats at each site
ShelveLoc - A factor with levels Bad, Good and Medium indicating the quality of the shelving location for the car seats at each site
Age - Average age of the local population
Education - Education level at each location
Urban - A factor with levels No and Yes to indicate whether the store is in an urban or rural location
US - A factor with levels No and Yes to indicate whether the store is in the US or not
