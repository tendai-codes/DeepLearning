# Bank Customer Churn Prediction Using Artificial Neural Networks

## Problem

This project analysed bank customer data to model patterns associated with customer attrition and support prediction of churn outcomes using an artificial neural network.

## Objective

- Prepare customer feature data for supervised classification modelling
- Encode categorical variables and scale numerical inputs for ANN training
- Train an artificial neural network to predict churn outcomes
- Evaluate classification performance using confusion matrix and accuracy

## Approach

- Loaded the `Churn_Modelling.csv` dataset and separated predictors from the churn target
- Encoded geography and gender variables, then split the data into training and test sets
- Applied standardisation to the feature set before model training
- Built, trained, and evaluated a TensorFlow/Keras artificial neural network classifier

## Key Findings

- The model achieved an accuracy of **86.05%** on the test set
- The confusion matrix was `[[1516, 79], [200, 205]]`, showing stronger performance on non-churn cases than churn cases
- Categorical preprocessing and feature scaling were required before ANN training
- The notebook implemented a complete binary classification workflow for customer churn prediction
