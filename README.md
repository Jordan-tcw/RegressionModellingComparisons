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
1. Sales - Unit sales (in thousands) at each location
2. CompPrice - Price charged by competitor at each location
3. Income - Community income level (in thousands of dollars)
4. Advertising - Local advertising budget for company at each location (in    thousands of dollars)
5. Population - Population size in region (in thousands)
6. Price - Price company charges for car seats at each site
7. ShelveLoc - A factor with levels Bad, Good and Medium indicating the quality of the shelving location for the car seats at each site
8. Age - Average age of the local population
9. Education - Education level at each location
10. Urban - A factor with levels No and Yes to indicate whether the store is in an urban or rural location
11. US - A factor with levels No and Yes to indicate whether the store is in the US or not
