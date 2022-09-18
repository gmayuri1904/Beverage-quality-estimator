# Beverage Quality Estimator
Predicting the Quality of Red Wine using Machine Learning Algorithms for Classification, Resampling techniques, Data Visualizations and Data Analysis, accuracy measurements and hyperparameter tuning.

# Description

## Context
The datasets is related to red wine variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality.

## Content
Input variables (based on physicochemical tests):
1 - fixed acidity 
2 - volatile acidity 
3 - citric acid 
4 - residual sugar 
5 - chlorides 
6 - free sulfur dioxide 
7 - total sulfur dioxide 
8 - density 
9 - pH 
10 - sulphates 
11 - alcohol 

Output variable (based on sensory data): 
12 - quality (score between 0 and 10) 

# #Classificaion
Originally a regression problem, I have converted it to a classificaion by setting a threshold of 7.5score on the depend variable. wines with quaility score higher than 7.5 will be classified as good, else poor.  This allows us to practice with hyper parameter tuning, looking at the ROC curve and the AUC value, and feature engineering to further better the performance.

##Inspiration
Use machine learning to determine which physiochemical properties make a wine 'good'!

## Acknowledgements
This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality 
