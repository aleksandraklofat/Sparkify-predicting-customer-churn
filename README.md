# Sparkify-predicting-customer-churn
Predicting customer churn using Spark
## Background
This project predict customer churn in a fictional music app Sparkify using Apache Spark as tool. 
We analyse a large database of users playing music in the Sparkify app in order to predict their churn rates based on different characteristics. 
## Files
This repository contains following files: 
- mini_sparkify_event_data.json: a small subset of the original data used to train and test our model;
- Sparkify.ipynb: Jupyter notebook containing the analysis
- Sparkify.html: a HTML version of the Jupyter notebook 
## Installation
The required packages include among others:
- Python 3
- Pyspark
- SQL
- Spark
- numpy
- pandas
- matplotlib 
## Approach and Results
In order to predict customer churn rates first I transformed data into numerical values and also constructed new features. 
In the second step I implemented following algorithms enabled by Spark:

1. Logistic Regression
2. Random Forest
3. Gradient Boosting

In the first run the algorithms were specified without parameter tuning in order to improve their time performance.
The results of the first run were:
- Logistic Regression with F1 score 0.7625630322111933
- Random Forest with F1 score 0.8407021771723214
- Gradient Boosing with F1 score 0.9937213958436153

After the first run I chose gradient boosting for further tuning. After parameter tuning gradient boosting scored even bettter on this dataset with F1 score over 0.995. This points towards overfitting. This result is not surprising due to the fact that the subste of data at hand contains not that many churned users. It needs to be tested on the whole dataset. 

## Blog post about the project

I have also created a small blog post about analysing Sparkify dataset, which can be found on Medium().   

