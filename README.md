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
In summary, the Easy Ensemble AdaBoost Classifier model had the highest balanced accuracy score by the far. At first glance, this tells us that it is the most accurate model for predicting credit risk. It is important to note that all six machine learning models had very low precision scores when it comes to predicting high risk. This means that none of the models can accurately predict high credit risk which could lead to a lot of loans being denied under false pretenses. However, the Easy Ensemble AdaBoost Classifier model does have a high recall score for both high and low credit risk. It predicts 92% of high credit risk instances and 94% of low credit risk instances. In this case, the F1 score is probably not as important as precision and recall because viewing the scores as two seperate numbers tells us more about the model's effectiveness in predicting credit risk. In this case, having a high recall is probably more important than precision because it ensures that the bank isn't making too many risky investments. For this reason, my recommendation would be to use the Easy Ensemble AdaBoost Classifier model to predict credit risk.
