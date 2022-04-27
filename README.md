# Credit_Risk_Analysis

## Overview
Data analysts were asked to examine credit card data from a peer-to-peer lending services company in order to determine credit risk. Supervised machine learning was used to find out which model would perform the best with an unbalanced dataset. Several models have been applied and used to predict credit risk.

## Dependencies
- Jupyter Notebook
- Python v3.x
  -  Dependencies
      -  Numpy
      -  Pandas
      -  Pathlib
      -  Collections
      -  SKLearn
      -  ImbalancedLearn

## Results

### Naive Random Oversampling

![Pic 1](https://github.com/Akotovets1/Credit_Risk_Analysis/blob/main/Module-17-Challenge/images/1.png)

1.Balanced Accuracy: 0.6497536370265621

2.Precision: The precision is low for High-risk loans and is high for Low-risk loans.

3.Recall: High/Low risk = 0.62/0.68



### SMOTE Oversampling

![Pic 2](https://github.com/Akotovets1/Credit_Risk_Analysis/blob/main/Module-17-Challenge/images/2.png)

1.Balanced Accuracy: 0.6443721269403855

2.Precision: The precision is low for High-risk loans and is high for Low-risk loans.

3.Recall: High/Low risk = 0.63/0.66


### Undersampling

![Pic 3](https://github.com/Akotovets1/Credit_Risk_Analysis/blob/main/Module-17-Challenge/images/3.png)

1.Balanced Accuracy: 0.6443721269403855

2.Precision: The precision is low for High-risk loans and is high for Low-risk loans.

3.Recall: High/Low risk = 0.61/0.45 


### Combination Under-Over Sampling

![Pic 4](https://github.com/Akotovets1/Credit_Risk_Analysis/blob/main/Module-17-Challenge/images/4.png)

1.Balanced Accuracy:  0.529127435931526

2.Precision: The precision is low for High-risk loans and is high for Low-risk loans.

3.Recall: High/Low risk = 0.70/0.57



### Balanced Random Forest Classifier

![Pic 5](https://github.com/Akotovets1/Credit_Risk_Analysis/blob/main/Module-17-Challenge/images/5.png)

1.Balanced Accuracy: 0.7877672625306695

2.Precision: The precision is low for High-risk loans and is high for Low-risk loans.

3.Recall: High/Low risk = 0.67/0.91

### Easy Ensemble AdaBoost Classifier

![Pic 6](https://github.com/Akotovets1/Credit_Risk_Analysis/blob/main/Module-17-Challenge/images/6.png)

1.Balanced Accuracy: 0.9316600714093861

2.Precision: The precision is low for High-risk loans and is high for Low-risk loans.

3.Recall: High/Low risk = 0.67/0.91


## Summary

For this dataset, the Easy Ensemble AdaBoost Classifier is the best model because it has 0.93 balanced accuracy (the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model).
The Easy Ensemble AdaBoost Classifier also has the highest recall score (the better model needs to has the recall score closer to 1).

So, the best supervised machine learning model for further credit card analysis is the Easy Ensemble AdaBoost Classifier. Out of the six machine learning algorithms tested, Easy Ensemble AdaBoost Classifier performed the best overall.
