# Linear-Regression
Summary of the task:
The repository contains python code used to train and build a machine learning model using simple linear regression. A small dataset was used consisting of two columns (height and weight). The data was first split into the training set and the test set; tools from the Scikit Learn Library were then used to build the main model.
Creating a Machine Learning model to predict the real estate prices in India. We are going to use the dataset from Kaggle.com. We are also going to create a single page website which will provide the front end to access our model for predictions.

Below data science concepts are used in this project

Data loading and cleaning
Outlier detection and removal
Feature engineering
Dimensionality reduction
Gridsearchcv for hyperparameter tunning
K fold cross validation
Technology and tools used in this project

Python
Numpy and Pandas for data cleaning
Matplotlib for data visualization
Sklearn for model building
Google Colaboratory Notebook
Python flask for http server

Steps:

We will first build a model using sklearn and linear regression using banglore home prices dataset from kaggle.com.
Second step would be to write a python flask server that uses the saved model to serve http requests.
Third component is the website built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price.
