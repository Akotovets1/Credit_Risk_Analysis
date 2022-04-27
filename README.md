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



### SMOTE Oversampling



### Undersampling


### Combination Under-Over Sampling



### Balanced Random Forest Classifier


### Easy Ensemble AdaBoost Classifier



## Summary

When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.


The oversampling, undersampling, and combination sampling algorithms' performance were relatively the same. Balanced Random Forest Classifier had a higher balanced accuracy score than the previous algorithms tested, but it was not good enough for predicting credit risk.

Out of the six supervised machine learning algorithms tested, Easy Ensemble AdaBoost CLassifier performed the best overall.  It had a balanced accuracy score, along with high precision and recall scores.  It also had a high specificity score, which means this algorithm correctly determined actual negatives 91% of the time, and a high F1 score.  This means the harmonic mean of precision and recall were 0.97 out of 1.0.