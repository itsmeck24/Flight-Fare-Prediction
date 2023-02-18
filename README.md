# Flight-Fare-Prediction

## Problem Statement

Travelling, particularly by air, has become increasingly prevalent in recent years, with air travel gaining popularity compared to a decade ago. This trend can be attributed to several factors, including intensified competition among airlines, rising individual and household incomes, and a shift in mindset towards prioritizing time savings over the slightly higher cost of air travel.

## About 
The aim of this project is to predict the flight ticket prices based on certain features. I obtained a [dataset](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh) from Kaggle for this project. 
The dataset includes the following features: 
  Airline, Date of Journey, Source, Destination, Route, Departure Time, Arrival Time, Duration, Total Stops, Additional Information, and Price.
 
 The project is divided into three parts:
 * Exploratory Data Analysis (EDA)
 * Feature Engineering
 * Model Building and Evaluation
 
 ### Exploratory Data Analysis (EDA)

The Exploratory data analysis (EDA) for a flight fare prediction model involves getting an understanding of the dataset and identifying key observations and trends in the data. This can be done by importing the necessary libraries and dataset, and using various functions and include identifying missing values in the dataset, examining the distribution of numerical variables, analyzing categorical variables, identifying outliers, and exploring the relationship between independent features and the dependent variable 'price'.

### Feature Engineering

In this part, we try to note any correlations between variables and the output variable 'price'. In the case of flight fare prediction, it may be necessary to separate the cities in the 'Route' column, and convert various columns such as 'Arrival_Time', Departure_Time,'Duration', and 'Total_Stops' to appropriate formats.

I also try to convert categorical data, or text data, into numbers, which our predictive models can better understand i.e, used LabelEncoder and OneHotEncoder.

### Model Building and Evaluation

This part includes: 

* Creating the models, i.e., linear regression and random forest regressor, and fit them to the training data.
* Make predictions on the test set using the fitted models and evaluate their performance using appropriate metrics such as mean squared error (MSE) or R-squared.
* Comparing the performance of the two models and choose the one with better accuracy.

Finally, I obtained the following approximate accuracies:

* Linear Regression: 72.57 %
* Random Forest Regressor: 97.46 %
