# Predict-the-Happiness-on-TripAdvisor-
Predict the Happiness on TripAdvisor reviews using Dense Neural Network with Keras 

In the past several years, Neural Networks (NNs) have become the state-of-the-art solution for many applications.

Keras: is an easy library build on top of Tensorflow and Theano which is in python and the right place to start for beginners.
here is keras documentation link:https://keras.io/

It internally calls Tensorflow libary for NNs.

## Problem: 
TripAdvisor is the world's largest site where you can compare and book hotels, flights, restaurants etc. The data set provided in this challenge consists of a sample of hotel reviews provided by the customers. Analyzing customers reviews will help them understand about the hotels listed on their website i.e. if they are treating customers well or if they are providing hospitality services as expected.

In this problem, we have to predict if a customer is happy or not happy.

## Data-set Description:
We have three two files train.csv and test.csv. The training data has 38932 rows, while the test data has 29404 rows.

variables: User_ID (unique ID of the customer), Description (description of the review posted), Browser_Used (browser used to post the review), Device_Used (device used to post to review), Is_Response (target variable).

We are interested only in 2 columns. 'Description' which contains hotel reviews given by different users and 'Is_Response' which keeps the record of 'happy' or 'not_happy'. So, in Essence, this is simply a 2-class sentiment analysis problem.

## Problem solving steps:
1. Prepare Data
2. Feature Extraction
3. Build the Model
4. Train the Model
5. Checking Performance

