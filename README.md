# Industrial Copper Modeling Project
## Introduction
### This project aims to develop two machine learning models for the copper industry to address the challenges of predicting selling prices and lead classification. Manual predictions can be time-consuming and may not result in optimal pricing decisions or accurately capture leads.

### The models will utilize advanced techniques such as data normalization, outlier detection and handling, handling data in the wrong format, identifying the distribution of features, and leveraging tree-based models, specifically the decision tree algorithm, to predict the selling price and leads accurately.
## Regression Model Details
### The copper industry deals with less complex data related to sales and pricing. However, this data may suffer from issues such as skewness and noisy data, which can affect the accuracy of manual predictions. A machine learning regression model can address these issues by utilizing advanced techniques such as data normalization, outlier detection and handling, handling data in the wrong format, identifying the distribution of features, and leveraging tree-based models, specifically the decision tree algorithm.
## Classification Model Details
### Another area where the copper industry faces challenges is in capturing leads. A lead classification model evaluates and classifies leads based on how likely they are to become a customer. The STATUS variable can be used, with WON considered as Success and LOST as Failure. Data points other than WON and LOST STATUS values should be removed.
## Solution
### The solution includes the following steps:

### 1.Exploring skewness and outliers in the dataset.
### 2.Transforming the data into a suitable format and performing any necessary cleaning and pre-processing steps.
### 3.Developing a machine learning regression model that predicts the continuous variable ‘Selling_Price’ using the decision tree regressor.
### 4.Developing a machine learning classification model that predicts the Status (Won/Lost) using the decision tree classifier.
### 5.Creating a Streamlit page where you can insert each column value and get the Selling_Price predicted value or Status (Won/Lost).
## Requirements
### This project requires the following libraries to be installed:

### * NumPy
### * Pandas
### * Scikit-learn
### * Streamlit
