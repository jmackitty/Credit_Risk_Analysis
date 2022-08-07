# Credit_Risk_Analysis

## Overview of the analysis: 
The purpose of this analysis was to use machine learning models to predit credit risk for loans. We tested multiple models to see how well each performed, and so we can determine which model would be the best model to use in the future for the most accurate results.

## Results: 
We analyzed the results of 6 machine learning models:

* RandomOverSampler: The balanced accuracy score is almost 65%. The high_risk precision is 1% with a recall of 71%. The low_risk precision is 100%.

<img width="376" alt="RandomOversampler" src="https://user-images.githubusercontent.com/99056132/183273655-be4034e1-240c-4bfb-b1bb-9fd6e2f59ad5.png">

* SMOTE: The balanced accuracy score is almost 66%. The high_risk precision is 1% with a recall of 63%. The low_risk precision is 100%.
<img width="370" alt="SMOTE" src="https://user-images.githubusercontent.com/99056132/183273662-d83535ca-5cbd-4ade-b4ca-9d54738460f4.png">

* ClusterCentroids: The balanced accuracy score is around 54%. The high_risk precision is 1% with a 69% sensitivity result. Therefore, the low_risk precision is 100% with a sensitivity result of 40%.

* SMOTEENN: The balanced accuracy score is almost 64%. The high_risk precision is 1% with a recall of 68%. The low_risk precision is 100%.
<img width="367" alt="SMOTEENN" src="https://user-images.githubusercontent.com/99056132/183273668-c7d34085-350c-4a57-9eaf-026550467d0f.png">

* BalancedRandomForestClassifier: The balanced accuracy score is almost 79%. The high_risk precision is 4% with a recall of 67%. The low_risk precision is 100%.
<img width="377" alt="RandomForest" src="https://user-images.githubusercontent.com/99056132/183273672-560f54c4-a33c-495a-ba51-90c510645b91.png">

* EasyEnsembleClassifier: The balanced accuracy score is almost 93%. The high_risk precision is 7% with a recall of 91%. The low_risk precision is 100%.
<img width="367" alt="EasyEnsemble" src="https://user-images.githubusercontent.com/99056132/183273678-18f55932-f902-408a-97ee-996fbf9ccbea.png">

## Summary: 
The most accurate model is the EasyEnsembleClassifier, but this still has a low precision when it comes to high_risk. This increases the chances of the bank granting loans/mortgages to high risk customer. I would continue to work with the EasyEnsembleClassifier to try to get the high risk precision to increase, but this wo
