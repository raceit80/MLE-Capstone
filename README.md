# Machine Learning Engineer - Starbucks-Capstone-Project

Foobar is a Python library for dealing with word pluralization.

## Installation

Python 3.x
Libraries used:
Numpy
Pandas
Matplotlib
Seaborn
JSON, Math, Datetime, OS, Collections, Random
Sklearn Helpers (GridSearchCV, StratifiedShuffleSplit, train_test_split, ConfustionMatrix, MinMaxScaler)
SKlearn Models(LR, SVM, GradBoost, RandomForrest)

## Project Motivation

This project is a capstone challenge for Machine Learning Engineer Nanodegree from Udacity. The objective of this project is to explore, analyze, model the Starbucks offer dataset and recommend a model that predicts the offer completion success rate. 


## File Descriptions
This repository includes the following two notebooks and their HTML versions:

#### Data Exploration, Cleaning & Feature Engineering notebook
In this notebook, I explored the given dataset and cleaned the dataset using OHE, Categorical values and feature engineered (feature scaling, normalization) to make it machine learning ready.
#### Modeling, Evaluation and Findings notebook
In this notebook, I performed modeling reviewed the model dataset and checked its validity, split the dataset into train, test and validation datasets, wrote functions to evaluate the metrics (Confusion Matrix, TP, TN, FP, FN and F1 and F2 scores)
I benchmarked using Sklearn Logistic Regression (LR).
Trained, evaluated and compared 3 more models - SVM, Gradient Boost, and RandomForrest.

## Results
#### Data Insights:
There are 57% Males and 41% Females in the given dataset
Mean age of the customers in this dataset is 54 
Income varies from $30000 to $120,000 with a mean of $64,404
Total Offer success rate (Offer completed/Offer viewed) is ~50% 
Females respond to offers better than Males (Female: 58% and Male:45%)
Baby Boomers are the top responders to offers (53%). 
Older age group respond to offers more than younger age group

#### Model Results:
Logistic Regression (Benchmark model) 69% accuracy score. (Precision:0.71, Recall: 0.85,  Accuracy: 0.69,  F1: 0.78,  F2: 0.82)
Support Vector Machine -  71% accuracy score. (Precision:0.75, Recall: 0.81,  Accuracy: 0.71,  F1: 0.78,  F2: 0.80)
Gradient Boost is the best performing model with 90% accuracy score. (Precision:0.91, Recall: 0.93,  Accuracy: 0.90,  F1: 0.92,  F2: 0.92)
Random Forrest Classifier - 75% accuracy score. (Precision:0.77, Recall: 0.85,  Accuracy: 0.75,  F1: 0.81,  F2: 0.84)
