# Credit_Risk_Analysis

## Overview of the Analysis
This analysis was conducted to use various machine learning methods in evaluting the credit risk of customers in a provided dataset. It had the following 3 parts: 
1. Resampling Model with imbalanced-learn and scikit-learn libraries using the RandomOverSampler algorithm.
2. Combinatorial approach of over- and undersampling with imbalanced-learn and scikit-learn libraries using the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithm.
3. Undersampling ClusterCentroids algorithm with imblearn.ensemble library. I trained and compared two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model.

## Results: 
The results for each of the 6 modules is as follows:
* Naive Random Oversampling results: The accuracy score is 64%; the precision is 1% for high_risk and 100% for low_risk; and the recall is 69% and 59%, respectively.
  ![Naive Random Oversampling](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/Naive%20Random%20Oversampling.png)

* SMOTE Oversampling results: The accuracy score is 66%; the precision is 1% for high_risk and 100% for low_risk; and the recall is 63% and 59%, respectively.
  ![SMOTE oversampling](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/SMOTE%20oversampling.png)

* Undersampling results: The accuracy score is 66%; the precision is 1% for high_risk and 100% for low_risk; and the recall is 69% and 40%, respectively.
  ![Undersampling](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/Undersampling.png)

* Combination (over and undersampling) results: The accuracy score is 54%; the precision is 1% for high_risk and 100% for low_risk; and the recall is 72% and 57%, respectively.
  ![Combination(over and undersampling)](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/Combination(over%20and%20undersampling).png)

* Balanced Random Forest Classifier results: The accuracy score is 84%; the precision is 4% for high_risk and 100% for low_risk; and the recall is 77% and 90%, respectively.
  ![Balanced Random Forest Classifier](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/Balanced%20Random%20Forest%20Classifier.png)

* Easy Ensemble AdaBoost Classifier results: The accuracy score is 93%; the precision is 7% for high_risk and 100% for low_risk; and the recall is 91% and 94%, respectively.
  ![Easy Ensemble AdaBoost Classifier results](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/Easy%20Ensemble%20AdaBoost%20Classifier.png)

## Summary: 
Overall, the Easy Ensemble AdaBoost Classifier was the best model to use. It yielded the higest accuracy, precision and recall scores over all models, and substantially more than the logistic regression models (all four). I would suggest that we use the same model for our credit risk assessment purposes.
