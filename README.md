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
3. Gradient Boosted Trees

In the first run the algorithms were specified without parameter tuning in order to improve their time performance.
After the first run 

## Blog post about the project


