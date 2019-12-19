# Sparkify DSND Capstone project
### Building Customer Churn Predictive Model Using SPARK

Sparkify is a fictional music streaming platform created by Udacity.   Provided user log data contains demographic, user activities, timestamps, and additional related information. 
With the provide logs data, a functional model has been developed for predicting users at risk of churn, and thus, sending promotional offers or value-added content to retain the users.

This repository contains the EDA and model development code for Sparkify Capstone Project. More information is available on a [Medium Blog Post](https://medium.com/).

Mini, medium, and large datasets(only on AWS public) are provided for analysis. Mini and medium scale datasets were used on the Udacity cluster, and IBM Watson studio spark environments.


## Table of Contents
  - Installation
  - Project Motivation
  - Files Description
  - Models
  - Methodology
  - Results and Future work
  - Credits and Acknowledgements
  
  
## Installation
  
    This project uses the following software and Python libraries:

    Python
    Spark
    Pyspark
    pandas
    Matplotlib

Anaconda environment can be utilized to run and execute provided Jupyter Notebook.

## Project Motivation

#### developing Skills of:

- Working/wrangling large datasets using Spark via PySpark and Spark
- Usage of Spark ML machine learning APIs to develop and tune models

## Files Description

- Sparkify.ipynb -  demonstrates the process of using Pyspark to explore the data and build the model.
- Sparkify_IBM_watson.ipynb - demonstrates the process of using Pyspark to explore the data and build the model using the IBM Watson product.

## Models:
- Logistic Regression
- Random Forest
- Gradient Boosted Trees

## Methodology:
1. Load data
2. EDA and Define customer churn
3. Feature engineering
4. Modeling 
5. Evaluation
6. Hyperparameter Tuning

## Results and Future work

- Preprocess data and create New DateTime related features
- Split the dataset into train, test, and built pipeline using three machine learning models.
- Tune hyperparameters using F1 score metric to optimize.

Outputs are generated using mini and medium-sized dataset, which might have introduced a slight imbalance in the data. Feature selection plays a significant role in model predictions. The feature synthesis can be improved with more domain knowledge and expertise. Many ignored features can be converted into consumable form to identify if users are more likely to churn when they log in via mobile versus desktop, Predictive performance in relation to the average length of a given user’s session. A more robust feature set can be developed with more time.

The main findings of the code can be found at the post available [here](https://medium.com/).

## Credits and Acknowledgements

[Udacity](https://www.udacity.com/) for curating a program with intensive projects.

