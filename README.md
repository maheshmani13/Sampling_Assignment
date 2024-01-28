# Credit Card Fraud Detection Model Evaluation on different Samplings

## Overview

This repository contains code for evaluating different machine learning models on a credit card fraud detection dataset. The goal is to assess the performance of various sampling techniques combined with different classification models on an imbalanced dataset.

## Dataset

The dataset used for this analysis is obtained from [Creditcard_data.csv](https://raw.githubusercontent.com/AnjulaMehto/Sampling_Assignment/main/Creditcard_data.csv). It contains features related to credit card transactions and a binary target variable indicating whether a transaction is fraudulent or not.

## Sampling Techniques

Following 5 sampling Techniques were used:
1. Random Under Sampler 
2. Random Over Sampler 
3. SMOTE 
4. Near Miss 
5. Stratified KFold

## Models

Following 5 models were applied on the sampled dataset:
1. Logistic Regression 
2. Decision Tree Classifier
3. Random Forest Classifier 
4. Support Vector Classifier (SVC) 
5. KNN Classifier 

## Sample Size

The Sample size was calculates using the following formula: n = Z^2(p(1 – p)/m^2) where: 
n = sample size
Z = z-value (for 99% confidence interval, Z = 2.576)
p = proportion of the minority class (taken as 0.5 for a balanced dataset)
m = margin of error (taken as 0.05 for a sample size of 1000)

## Results 
![](https://github.com/maheshmani13/Sampling_Assignment/blob/main/Results.png)
