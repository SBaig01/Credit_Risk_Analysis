# Credit_Risk_Analysis

## Overview of the Analysis
This analysis was conducted to use various machine learning methods in evaluting the credit risk of customers in a provided dataset. It had the following 3 parts: 
1. Resampling Model with imbalanced-learn and scikit-learn libraries using the RandomOverSampler algorithm.
2. Combinatorial approach of over- and undersampling with imbalanced-learn and scikit-learn libraries using the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithm.
3. Undersampling ClusterCentroids algorithm with imblearn.ensemble library. I trained and compared two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model.

## Results: 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
* Naive Random Oversampling results: The accuracy test is 64%, the precision for high_risk is 1% and low_risk is 100%, and the recall is 74%
 ![Naive Random Oversampling](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/Naive%20Random%20Oversampling.png)
* SMOTE oversampling results
 ![SMOTE oversampling](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/SMOTE%20oversampling.png)
* Undersampling results
 ![Undersampling](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/Undersampling.png)
* Combination(over and undersampling) results
 ![Combination(over and undersampling)](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/Combination(over%20and%20undersampling).png)
* Balanced Random Forest Classifier results
 ![Balanced Random Forest Classifier](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/Balanced%20Random%20Forest%20Classifier.png)
* Easy Ensemble AdaBoost Classifier results
 ![Easy Ensemble AdaBoost Classifier results](https://github.com/SBaig01/Credit_Risk_Analysis/blob/0095debfe3bc01aad6b264e58284e42087d8bada/Images/Easy%20Ensemble%20AdaBoost%20Classifier.png)

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
