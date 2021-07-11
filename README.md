# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis

The purpose of this project is to apply machine learning to solve a real-world challenge: credit card risk. In the Deliverable 1, using the knowledge of the imbalanced-learn and scikit-learn libraries, evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, I uded to the oversampling RandomOverSampler and SMOTE algorithms, and then I used to the undersampling ClusterCentroids algorithm. By using these algorithms, I could be resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

In Deliverable 2, By using the knowledge of the imbalanced-learn and scikit-learn libraries,I used to a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. Using the SMOTEENN algorithm, I could be resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

Finaly for Deliverable 3, By using the knowledge of the imblearn.ensemble library, I used to train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using both algorithms,I could be resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

## Outline of the project

  . Deliverable 1: Use Resampling Models to Predict Credit Risk
  
  . Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
  
  . Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
  
  . Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)
  
 ## Resources
 
  . Data Source: LoanStats_2019Q1.csv
  
  . Software: Python,Jupyter Notebook 
  
 ## Results
 
 ### Deliverable 1: Use Resampling Models to Predict Credit Risk
 
 ##### Results Table 1: Balanced Random Forest Classifier
 
 ![image](https://user-images.githubusercontent.com/80365882/125183263-f92bb780-e1c9-11eb-95e2-5a66c52b7930.png)

 The above results show us, The balanced accuracy score is 79%.The high_risk precision is about 4% only with 68% sensitivity which makes a F1 of 7%.The low_risk population, its precision is almost 100% with a sensitivity of 90%.
 
  ### Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
  
  ##### Results Table 2: Easy Ensemble AdaBoost Classifier
  
 ![image](https://user-images.githubusercontent.com/80365882/125183271-09dc2d80-e1ca-11eb-86fc-200bc2db9d42.png)

The above Results of SMOTEENN algorithm to Predict Credit Risk show us, The balanced accuracy score is 92%.The high_risk precision is about 9% only with 89% sensitivity which makes a F1 of 16%.The low_risk population, its precision is almost 100% with a sensitivity of 94%.
 

### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
 
  ##### Results Table 3: Naive Random Oversampling
 
![image](https://user-images.githubusercontent.com/80365882/125183304-62abc600-e1ca-11eb-802d-d5745b32aed2.png)
 
The above Results of Naive Random Oversampling show us, The balanced accuracy score is 66%.The high_risk precision is about 1% only with 66% sensitivity which makes a F1 of 2%.The low_risk population, its precision is almost 100% with a sensitivity of 67%.
 
 
 ##### Results Table 4: SMOTE Oversampling
  
![image](https://user-images.githubusercontent.com/80365882/125183311-70614b80-e1ca-11eb-8f31-812160033e43.png)

The above SMOTE Oversampling show us, The balanced accuracy score is 63%.The high_risk precision is about 1% only with 62% sensitivity which makes a F1 of 2%.The low_risk population, its precision is almost 100% with a sensitivity of 64%.
 

 ##### Results Table 5: Undersampling
 
![image](https://user-images.githubusercontent.com/80365882/125183315-7c4d0d80-e1ca-11eb-8b39-598f57880c46.png)

From the above table results , The balanced accuracy score is 52%.The high_risk precision is about 1% only with 61% sensitivity which makes a F1 of 2%.The low_risk population, its precision is almost 100% with a sensitivity of 45%.
 
  ##### Results Table 6: Combination (Over and Under) Sampling
  
![image](https://user-images.githubusercontent.com/80365882/125183323-8838cf80-e1ca-11eb-84ba-88bb81ce0561.png)

Combination (Over and Under) Sampling table results show us , The balanced accuracy score is 62%.The high_risk precision is about 1% only with 70% sensitivity which makes a F1 of 2%.The low_risk population, its precision is almost 100% with a sensitivity of 54%.

## Summary

Almost all the models used to perform weak precision in determining if a credit risk is high.But the Ensemble models brought a lot more improvment specially on the sensitivity of the high risk credits.
From the results of output, I recommend Easy Ensemble AdaBoost Classifier model becouse of it's high accuracy score and good balance of precision and recall scores.from all the models.
 
