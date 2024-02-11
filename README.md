# Salifort_Motors
A predictive model for Salifor Motors HR department to predict employee turn over

## Overview 

The goal of this project was to create a predictive model that predicts employee turnover of salifort motors HR department.
We trained five models which are LogisticRegression , NaiveBayes , DecisionTree , RandomForest and XGBOOST.
The champion model was Random Forest with F1-score 0.955

## Business Understanding 

The HR department at Salifort Motors wants to take some initiatives to improve employee satisfaction levels at the company. They collected data from employees, but now they don’t know what to do with it , They have the following question: what’s likely to make the employee leave the company?
our goal in this project is to analyze the data collected by the HR department and to build a model that predicts whether or not an employee will leave the company.
If we can predict ***employees likely to quit***, it might be possible to identify factors that contribute to their leaving. Because it is time-consuming and expensive to find, interview, and hire new employees, increasing employee retention will be beneficial to the company.

## Data Understanding

The HR emplyee retention data came from Kaggle.
The data consisted of approximately 15000 employee and 10 features. The features included information on employees satisfaction and last evaluation, number of projects, average monthly hours, time spend at company , work accident , promotion in last five years , department and salary.

## Modeling and Evaluation 

We trained five models which are:
 - LogisticRegression
 - NaiveBayes
 - DecisionTree
 - RandomForest
 - XGBOOST
   
considering accuracy measures , for each model , we output a confusion matrix and four accuracy measures , they are
 - Accuracy
 - Precision
 - Recall
 - F1 Score
   
in this project , we care about both false positives and false negatives , this is because:
 - False Negatives means that the model inaccurately identified employees as staying , while they left.
 - False positives identified employees as leaving while they will stay, which will be time-consuming and expensive for HR department to find, interview, and hire new employees.

## Conclusion

This model can benefit the HR deparmtent to identify which *employees are likely to quit, it might be possible to identify factors that contribute to their leaving.
