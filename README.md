# Credit_Risk_Analysis

## Overview of Analysis

For this analysis, I need to solve a credit card risk challenge using machine learning. Since credit risk is an unbalanced classification problem, I need to employ different techniques to train and evaluate models with unblanaced classes. I will use the imbalanced-learn and scikit-learn libraries to build models using resampling. Then, I will oversample the data using RandomOverSampler and SMOTE, and undersample the data using ClusterCentroids. I will then combine the over and undersampling methods using SMOTEENN. Lastly, I will compare two machine learning models, BalancedRandomForestClassifies and Easy EnsembleClassifier, to predict credit risk. 

### Purpose

The purpose of this analysis is to determine whether these machine learning models should be used to predict credit risk.

## Results

### RandomOverSampler Model

* The balanced accuracy score is about 65%.

* The high_risk precision is 1% and its recall score is 62%.

* The low_risk precision score is 100% with a recall of 68%. The precision score is very high because the low_risk population is high.

![image info](./Resources/randomoversampler.png)

### SMOTE Model

* The balanced accuracy score is 61%.

* The high_risk precision is 1% and the recall is 55%.

* The low_risk precision is 100% and the recall is 67%.

![image info](./Resources/smote.png)

### ClusterCentroids Model

* The balanced accuracy score is 52%.

* The high_risk precision is 1% and the recall is 60%.

* The low_risk precision is 100% and the recall is 45%.

![image info](./Resources/clustercentroids.png)

### SMOTEENN Model

* The balanced accuracy score is 65%.

* The high_risk precision is 1% and the recall is 75%.

* The low_risk precision is 100% and the recall is 56%.

![image info](./Resources/smoteenn.png)

### BalancedRandomForestClassifier Model

* The balanced accuracy score is 79%.

* The high_risk precision is 4% and the recall is 67%.

* The low_risk precision is 100% and the recall is 91%.

![image info](./Resources/balancedrandomforestclassifier.png)

### EasyEnsembleClassifier Model

* The balanced accuracy score is 93%.

* The high_risk precision is 7% and the recall is 91%.

* The low_risk precision is 100% and the recall is 94%.

![image info](./Resources/easyensembleclassifier.png)

## Summary

