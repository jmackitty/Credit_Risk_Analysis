# Credit_Risk_Analysis

## Overview of the analysis: 
The purpose of this analysis was to use machine learning models to predit credit risk for loans. We tested multiple models to see how well each performed, and so we can determine which model would be the best model to use in the future for the most accurate results.

## Results: 
We analyzed the results of 6 machine learning models:

* RandomOverSampler: The balanced accuracy score is almost 65%. The high_risk precision is 1% with a recall of 71%. The low_risk precision is 100%.
https://github.com/jmackitty/Credit_Risk_Analysis/blob/main/RandomOversampler.png

* SMOTE: The balanced accuracy score is almost 66%. The high_risk precision is 1% with a recall of 63%. The low_risk precision is 100%.
https://github.com/jmackitty/Credit_Risk_Analysis/blob/main/SMOTE.png

* ClusterCentroids: The balanced accuracy score is around 54%. The high_risk precision is 1% with a 69% sensitivity result. Therefore, the low_risk precision is 100% with a sensitivity result of 40%.
https://github.com/jmackitty/Credit_Risk_Analysis/blob/main/ClusterCentroids.png

* SMOTEENN: The balanced accuracy score is almost 64%. The high_risk precision is 1% with a recall of 68%. The low_risk precision is 100%.
https://github.com/jmackitty/Credit_Risk_Analysis/blob/main/SMOTEENN.png

* BalancedRandomForestClassifier: The balanced accuracy score is almost 79%. The high_risk precision is 4% with a recall of 67%. The low_risk precision is 100%.
https://github.com/jmackitty/Credit_Risk_Analysis/blob/main/RandomForest.png

* EasyEnsembleClassifier: The balanced accuracy score is almost 93%. The high_risk precision is 7% with a recall of 91%. The low_risk precision is 100%.
https://github.com/jmackitty/Credit_Risk_Analysis/blob/main/EasyEnsemble.png

## Summary: 
The most accurate model is the EasyEnsembleClassifier, but this still has a low precision when it comes to high_risk. This increases the chances of the bank granting loans/mortgages to high risk customer. I would continue to work with the EasyEnsembleClassifier to try to get the high risk precision to increase, but this wo
