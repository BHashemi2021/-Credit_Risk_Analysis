# Credit Risk Analysis
Applying Supervised Machine Learning to Credit Risk Analysis

-------------------------
![Credit-risk-analysis.png](https://github.com/BHashemi2021/Credit_Risk_Analysis/blob/main/Resources/Images/Credit-risk-analysis.png)

-------------------------

## Background
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we will need to employ different techniques to train and evaluate models with unbalanced classes. Therefore, we have been tasked to use imbalanced-learn and scikit-learn libraries to build and evaluate such models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we will oversample the data using the RandomOverSampler and SMOTE algorithms, and later undersample the data using the ClusterCentroids algorithm. Then, we will use a combinatorial approach of over- and undersampling using the SMOTE-ENN algorithm. Next, we will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Finally, we will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

### What We are Creating

   1: Use Resampling Models to Predict Credit Risk
   2: Use the SMOTEENN Algorithm to Predict Credit Risk
   3: Use Ensemble Classifiers to Predict Credit Risk
   4: A Written Report on the Credit Risk Analysis 


## Oerview

In this analysis, we used a dataset with 96 different variables from loan applicants composed of 115675 costumers from which 68470 were low risk and 347 high risk applicants based on the type of data collected. In this analysis we try to prepared the uballenced dataset to predict credit risk score for the aforesaid banking institution.

## Results 

1: Using Resampling Models to Predict Credit Risk

We used different resampling methods to predict the credit risk. Prilimianry the accuracy score for the model was calculated about 66%, Figure 1.

### Figure 1: Accuracy score of the model

---------------------------
![1.1-accuracy_score.png](https://github.com/BHashemi2021/Credit_Risk_Analysis/blob/main/Resources/Images/1.1-accuracy_score.png)

---------------------------


The confusion matrix was also generated for the priliminry sampling method as shown in Figure 2.


### Figure 2: The confusion matrix

---------------------------
![1.2-confusion_matrix.png](https://github.com/BHashemi2021/Credit_Risk_Analysis/blob/main/Resources/Images/1.2-confusion_matrix.png)

---------------------------

The imbalanced classification report is shown n Figure 3.


### Figure 3: Imbalanced classification report

---------------------------
![1.3-imbalanced_classification_report.png](https://github.com/BHashemi2021/Credit_Risk_Analysis/blob/main/Resources/Images/1.3-imbalanced_classification_report.png)

---------------------------


### 2: Using the Synthetic Minority Over-sampling Technique (SMOTE)

To balance the lop-sided dataset we could use the SMOTE oversamping of the minoriy group. The method generated an accuracy score of around 64%.The confusion matrix and the imbalenced reports are shown in Figure 4.


### Figure 4: SMOTE confusion matrix and imbalanced classification report

---------------------------
![1.4-SMOTE.png](https://github.com/BHashemi2021/Credit_Risk_Analysis/blob/main/Resources/Images/1.4-SMOTE.png)

---------------------------

### 3: Using Ensemble AdaBoost Classifier Method

This method yielded a higher accuracy rate () than the other methods (93%) and generted more balanced variables of concern.


![1-5-Ensemble-AdaBoost.png](https://github.com/BHashemi2021/Credit_Risk_Analysis/blob/main/Resources/Images/1-5-Ensemble-AdaBoost.png)


## Summary

Having applied different sampling and machine learning models, including SMOTE-ENN Method that combines the SMOTE ability to generate synthetic examples for minority class and ENN ability to delete some observations from both classes identified as having different class between the observation’s class and its K-nearest neighbor majority class, it seems the models still could not reliably overcome the hugely lop-sided dataset and most will detect the approved applications better than the rejected ones. Although none of the models built based on this dataset are fit enough to generalize the model for future purposes as they may pose undue financial risks, but the Ensemble AdaBoost Classifier Method could be used for screening purposes due to its higher  accuracy rate.


 



