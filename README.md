# Credit_Risk_Analysis

## Overview
The purpose of this analysis was to predict credit risk using resampling models, the SMOTEEN algorithm, and ensemble classifiers.

## Results
### Random Oversampling
Balanced accuracy score: 0.67
![Random_Oversampling_Classification_Report](RandomOversampling.png)

### SMOTE Oversampling
Balanced accuracy score: 0.66
![SMOTE_Oversampling_Classification_Report](SMOTEOversampling.png)

### Undersampling
Balanced accuracy score: 0.57
![Undersampling_Classification_Report](Undersampling.png)

### Combination (Over and Under) Sampling
Balanced accuracy score: 0.64
![Combination_Sampling_Classification_Report](CombinationSampling.png)

### Balanced Random Forest Classifier
Balanced accuracy score: 0.78
![BalancedRandomForest_Classification_Report](BalancedRandomForestClassifier.png)

### Easy Ensemble AdaBoost Classifier
Balanced accuracy score: 0.93
![EasyEnsembleAdaBoost_Classification_Report](EasyEnsembleAdaBoostClassifier.png)

## Summary
In summary, the Easy Ensemble AdaBoost Classifier model had the highest balanced accuracy score by the far. At first glance, this tells us that it is the most accurate model for predicting credit risk. 
