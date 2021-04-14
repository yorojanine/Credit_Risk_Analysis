# Credit_Risk_Analysis

## Overview/Purpose:

The purpose of this challenge was to apply what we've learned about **supervised machine learning** and how it applies to credit card risk. 
According to the module, "Credit risk is an inherently unbalanced classification problem..." because good loans outweigh risky loans. 
Thus, the goal is to apply different techniques to test, train and assess models with unbalanced classes.
As such, the *imbalanced-learn* and *scikit-learn* libraries were used in the challenge for building models and resampling. 

With the credit card credit dataset (from LendingClub, a peer-to-peer lending services company) the following approaches were taken:

1. **Oversample** the data using:<br> >>*smaller class resampled to be larger*<br>  
      - RandomOverSampler
      - synthetic minority oversampling technique (SMOTE) algorithms<br><br>
2. **Undersample** the data using:<br> >>*the size of the majority class is decreased*<br>
      - ClusterCentroids algorithm<br><br>
3. **Combination approach** of "Over- & Under-" sampling the data using:
      - SMOTEENN algorithm (combines SMOTE and Edited Nearest Neighbors (ENN) algorithms)<br><br>

In addition, two new machine learning models (meant to reduce bias) were also included in the assessment to predict credit card risk:<br>

4. **BalancedRandomForestClassifier**<br>
5. **EasyEnsembleClassifier**<br>

## Results:



## Summary:

Summary of results
Recommendation
