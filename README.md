# Credit Risk Analysis

## Overview
In this project I used multiple methods of machine learning in order to predict the risk of a loan. Credit risk is unbalanced because good loans outnumber bad loans, so I employed several techniques to train and evaluate models with unbalanced classes. 

I trained and evaluated six different models in this analysis: Random Oversampler, SMOTE, Cluster Centroids, SMOTEENN, Balanced Random Forest Classifier, and Easy Ensemble Classifier. 

## Results
- Random Oversampling

![RandomOversampler](https://github.com/nicole-tough/Credit_Risk_Analysis/blob/main/Images/RandomOversampling.PNG)

- SMOTE Oversampling

![SMOTE](https://github.com/nicole-tough/Credit_Risk_Analysis/blob/main/Images/SMOTEOversampling.PNG)

- Cluster Centroids Undersampling

![Cluster Centroids](https://github.com/nicole-tough/Credit_Risk_Analysis/blob/main/Images/ClusterCentroidsUndersampling.PNG)

- SMOTEENN

![SMOTEEN](https://github.com/nicole-tough/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.PNG)

- Balanced Random Forest Classifier

![RandomForest](https://github.com/nicole-tough/Credit_Risk_Analysis/blob/main/Images/RandomForest.PNG)

- Easy Ensemble Classifier

![EasyEnsembleClassifier](https://github.com/nicole-tough/Credit_Risk_Analysis/blob/main/Images/EasyEnsemble.PNG)

## Summary

In general, the models did not do a very good job predicting high risk loans. The only model that accurately predicted high risk loans was the Random Forest Classifier. I would recommend using this model in the future when analyzing credit risk because it did the best job of predicting the unbalanced factor in this case. 

