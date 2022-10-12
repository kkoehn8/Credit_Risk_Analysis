# Credit_Risk_Analysis

## Overview of the Analysis
Our client would like us to use machine learning to predict credit risk for peer-to-peer loans. For the analysis we created models using six different methods and ran statistical results on the models to help us determine if there is a model that works better to help predict credit risk.

The analysis was conducted using Python and the following components:
 - Pandas
 - Scikit-learn
 - Imbalanced-learn

## Results

The initial data was preprocessed by performing the following steps:
 - the null columns where all values are null were dropped
 - the null rows were dropped
 - the loan status of "Issued" was removed
 - the interest rate was converted to a numerical data type
 - the target column was classified at low risk or high risk based on the how late the loan was
 - the training variables were created from string data types to numerical data types using the get dummies method
 - the target variables were created

 After the initial preprocessing of the data was performed six models were created for different methods. The different methods used were:
  - Oversampling
  - Undersampling
  - Combination (Over and Under) Sampling
  - Ensemble Learning

### Native Random Oversampling
The first model run for the Oversampling method was a Native Random Oversampling model.

The balanced accuracy score for this model is shown below:
![NRO_balance](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/NativeRandomOversampling_BalancedAccuracyScore.PNG)


The classification report showing precision and recall scores for this model is shown below:
![NRO_classification](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/NativeRandomOversampling_ClassificationReport.PNG)

### SMOTE Oversampling
The second model run for the Oversampling method was a SMOTE Oversampling model.

The balanced accuracy score for this model is shown below:
![SMOTE_balance](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/SMOTE_BalancedAccuracyScore.PNG)


The classification report showing precision and recall scores for this model is shown below:
![SMOTE_classification](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/SMOTE_ClassificationReport.PNG)

### Undersampling
The third model run was an Undersampling model.

The balanced accuracy score for this model is shown below:
![Under_balance](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/Undersampling_BalancedAccuracyScore.PNG)


The classification report showing precision and recall scores for this model is shown below:
![Under_classification](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/Undersampling_ClassificationReport.PNG)

### Combination (Over and Under) Sampling
The forth model run was the SMOTEENN model of the Comination (Over and Under) Sampling method. 

The balanced accuracy score for this model is shown below:
![SMOTEENN_balance](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/Combination_BalancedAccuracyScore.PNG)


The classification report showing precision and recall scores for this model is shown below:
![SMOTEENN_classification](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/Combination_ClassificationReport.PNG)

### Balanced Random Forest Classifier
The fifth model model run was the Balanced Random Forest Classifier model of the Ensemble Classifiers method.  

The balanced accuracy score for this model is shown below:
![BRF_balance](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/RandomForest_BalancedAccuracyScore.PNG)


The classification report showing precision and recall scores for this model is shown below:
![BRF_classification](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/RandomForest_ClassificationReport.PNG)

### Easy Ensemble AdaBoost Classifier
The final model run was also from the Ensemble Classifiers method and it was the Easy Ensemble AdaBoost Classifier. 

The balanced accuracy score for this model is shown below:
![EEABC_balance](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/EasyEnsemble_BalancedAccuracyScore.PNG)


The classification report showing precision and recall scores for this model is shown below:
![EEABC_classification](https://github.com/kkoehn8/Credit_Risk_Analysis/blob/main/Images/EasyEnsemble_ClassificationReport.PNG)

## Summary






Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.



