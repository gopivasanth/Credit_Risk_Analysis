# Credit_Risk_Analysis

## Overview
Using the LendingClub credit card dataset we intend to evaluate different machine learning models. 
The models used in this analysis were:

- RandomOverSampler
- SMOTE
- ClusterCentroids
- SMOTEENN
- BalancedRandomForestClassifier
- EasyEnsembleClassifier

## Purpose
The purpose of this analysis is to evaluate performance for each model and recommend if they should be used to predict credit risk. Listed below the performance of each model

### RandomOverSampler
- balanced accuracy score : 67.4%
- precision : 1%
- recall : 71%

![RandomOverSampler](https://github.com/gopivasanth/Credit_Risk_Analysis/blob/4a34012e503d64fd0a626d63e66ea9f54c1fed92/Images/RandomOverSampler.png)

### SMOTE
- balanced accuracy score : 66.2%
- precision : 1%
- recall : 63%

![Smote](https://github.com/gopivasanth/Credit_Risk_Analysis/blob/4a34012e503d64fd0a626d63e66ea9f54c1fed92/Images/SMOTE.png)

### ClusterCentroids
- balanced accuracy score : 54.4%
- precision : 1%
- recall : 69%

![ClusterCentroids](https://github.com/gopivasanth/Credit_Risk_Analysis/blob/4a34012e503d64fd0a626d63e66ea9f54c1fed92/Images/ClusterCentroids.png)

### SMOTEENN
- balanced accuracy score : 64.6%
- precision : 1%
- recall : 72%

![SMOTEENN](https://github.com/gopivasanth/Credit_Risk_Analysis/blob/4a34012e503d64fd0a626d63e66ea9f54c1fed92/Images/ClusterCentroids.png)

### BalancedRandomForestClassifier
- balanced accuracy score : 78.9%
- precision : 3%
- recall : 70%

![BalancedRandomForestClassifier](https://github.com/gopivasanth/Credit_Risk_Analysis/blob/4a34012e503d64fd0a626d63e66ea9f54c1fed92/Images/BalancedRandomForestClassifier.png)

### EasyEnsembleClassifier
- balanced accuracy score : 93.2%
- precision : 9%
- recall : 92%

![EasyEnsembleClassifier](https://github.com/gopivasanth/Credit_Risk_Analysis/blob/4a34012e503d64fd0a626d63e66ea9f54c1fed92/Images/EasyEnsembleClassifier.png)

## Summary
- all models have a low precision score

EasyEnsembleClassifier Model - best suited model due to below reasons
- highest precision of 9%
- this model also had the highest balanced accuracy score at 93.2%. 
- this model also had the highest recall at 92%

The high recall percentage means that it will likely be able to catch most fraud cases but the very low precision score means that it will likely also catch many non-fraud cases and classify them as fraud. 