# Credit Risk Analysis
Applying Supervised Machine Learning to Credit Risk Analysis

-------------------------
![Credit-risk-analysis.png](https://github.com/BHashemi2021/Credit_Risk_Analysis/blob/main/Resources/Images/Credit-risk-analysis.png)

-------------------------

## Background
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we will need to employ different techniques to train and evaluate models with unbalanced classes. Therefore, we have been tasked to use imbalanced-learn and scikit-learn libraries to build and evaluate such models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we will oversample the data using the RandomOverSampler and SMOTE algorithms, and later undersample the data using the ClusterCentroids algorithm. Then, we will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Finally, we will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

### What We are Creating

   1: Use Resampling Models to Predict Credit Risk
   2: Use the SMOTEENN Algorithm to Predict Credit Risk
   3: Use Ensemble Classifiers to Predict Credit Risk
   4: A Written Report on the Credit Risk Analysis 


## Oerview

In this analysis, we used a dataset with 96 different variables from loan applicants composed of 115675 costumers from which 68470 were low risk and 347 high risk applicants based on the type of data collected. 


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


2: Use the SMOTEENN Algorithm to Predict Credit Risk
The combinatorial SMOTEENN algorithm does the following:
An accuracy score for the model is calculated (5 pt)
A confusion matrix has been generated (5 pt)
An imbalanced classification report has been generated (5 pt)

3: Use Ensemble Classifiers to Predict Credit Risk
The BalancedRandomForestClassifier algorithm does the following:
An accuracy score for the model is calculated (2.5 pt)
A confusion matrix has been generated (2.5 pt)
An imbalanced classification report has been generated (5 pt)
The features are sorted in descending order by feature importance (5 pt)
The EasyEnsembleClassifier algorithm does the following:
An accuracy score of the model is calculated (2.5 pt)
A confusion matrix has been generated (2.5 pt)
An imbalanced classification report has been generated (5 pt)


4: A Written Report on the Credit Risk Analysis (README.md)
For this deliverable, you’ll write a brief summary and analysis of the performance of all the machine learning models used in this Challenge.

## Overview of the analysis: Explain the purpose of this analysis.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

The Requirements
Structure, Organization, and Formatting (6 points)
 

There is a title, and there are multiple sections (2 pt)
Each section has a heading and subheading (2 pt)
Links to images are working, and code is formatted and displayed correctly (2 pt).
Analysis (24 points)
The written analysis has the following:

Overview of the loan prediction risk analysis:

The purpose of this analysis is well defined (4 pt)
Results:

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)
Summary:

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)

