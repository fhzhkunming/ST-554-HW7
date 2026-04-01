# ST-554-HW7
This repository contains my work for ST 554 Homework 7. The goal of this assignment is to practice fitting multiple linear regression (MLR) and logistic regression models, including penalized or regularized versions such as LASSO, Ridge, and Elastic Net. The analysis uses the Wine Quality dataset from the UCI Machine Learning Repository, which includes physicochemical measurements of red and white wines along with quality ratings. Throughout the homework, I explore model fitting, variable selection, regularization, and model evaluation using both regression and classification frameworks.

The [data](https://archive.ics.uci.edu/dataset/186/wine+quality) describes the following variables:

Input variables (based on physicochemical tests)

1 - fixed acidity\
2 - volatile acidity\
3 - citric acid\
4 - residual sugar\
5 - chlorides\
6 - free sulfur dioxide\
7 - total sulfur dioxide\
8 - density\
9 - pH\
10 - sulphates\
11 - alcohol\
Output variable (based on sensory data):\
12 - quality (score between 0 and 10)
- Rather than try to predict quality, let’s make our target variable for fitting multiple linear regression
type models alcohol.
- For fitting logistic regression type models we’ll use the type of wine as the response variable.
