# Diabetes-prediction-using-SVM
created predictive system using SVM (Support Vector Machine Algorithm) 
# Detailed Explanation of the project
## Introduction
As title Suggets this project is about to predict whether the person is diabetic or not based on some raw data that available and by using one of the supervised machine learning algorithm called support vector machine
## Process 
First download the  Diabetes dataset from kaggle
Import all the libraries that needed in jupiter notebook
Load the dataset to jupiter notebook using pandas library
Now explore the data and then do the necessary data preprocessing steps
Find the labels and attributes in the dataset and separate them 
As all attributes are not in similar range we need to standardize the data for this import ScalerStandard and standardized the data by fit_transform method
Split the data into training data and testing data 
Train the svm model using the training data 
Predict the value by passing test data to the trained model
Find the accuracy of the model by using Accuracy_score
Finally create a Diabetes predictive system using the model
