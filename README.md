# Credit Risk Analysis
Applying Supervised Machine Learning to Credit Risk Analysis

-------------------------
![Credit-risk-analysis.png](https://github.com/BHashemi2021/Credit_Risk_Analysis/blob/main/Resources/Images/Credit-risk-analysis.png)

-------------------------

## Background
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we will need to employ different techniques to train and evaluate models with unbalanced classes. Therefore, we have been tasked to use imbalanced-learn and scikit-learn libraries to build and evaluate such models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we will oversample the data using the RandomOverSampler and SMOTE algorithms, and later undersample the data using the ClusterCentroids algorithm. Then, we will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Finally, we will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

### What We are Creating
This new assignment consists of three technical analysis and a written report, as it follows:
1: Use Resampling Models to Predict Credit Risk
2: Use the SMOTEENN Algorithm to Predict Credit Risk
3: Use Ensemble Classifiers to Predict Credit Risk
4: A Written Report on the Credit Risk Analysis (README.md)

1: Use Resampling Models to Predict Credit Risk
For all three algorithms, the following have been completed:
An accuracy score for the model is calculated (7.5 pt)
A confusion matrix has been generated (7.5 pt)
An imbalanced classification report has been generated (15 pt)


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

