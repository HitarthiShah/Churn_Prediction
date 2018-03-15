# Churn_Prediction
Given a training set of past churn data,  goal is to predict whether a person will leave the network (churn) or stay.  

1. Trained and built a decision tree model using the training data. 
2. Used the model to predict the outputs for the test data.

Data Description:
Each row represents a customer of the network, with the parameters for each customer described below.
The data consists of 20,000 customers, split into 90% (18,000) for training data and the remaining 10% (2,000) as test data (holdout). 
The labeled training data is in 'train.csv' and unlabeled test data is in 'test.csv'.

COLLEGE:  Is the customer college educated?

INCOME:   Annual income

OVERAGE:  Average overcharges per month

LEFTOVER: Average number of leftover minutes per month

HOUSE: Estimated value of dwelling (from census tract)

HANDSET_PRICE: Cost of phone

OVER_15MINS_CALLS_PER_MONTH: Average number of long calls (15 mins or over) per month

AVERAGE_CALL_DURATION: Average duration of a call

REPORTED_SATISFACTION: Reported level of satisfaction

REPORTED_USAGE_LEVEL: Self-reported usage level

CONSIDERING_CHANGE_OF_PLAN: Whether the customer considered changing their plan

LEAVE (Target variable): Did the customer stay or leave (churn)?
