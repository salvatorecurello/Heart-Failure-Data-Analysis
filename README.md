# Heart-Failure-Data-Analysis
## Overview
The report analyzes data from 299 heart failure patients admitted to a hospital in Pakistan during 2015. The goal was to predict patient survival using machine learning models.

The data contained 11 clinical features like age, blood pressure, diabetes status, and lab results. 

The target variable was whether the patient survived during the follow-up period.

After data cleaning, the report did exploratory analysis like looking for correlations and visualizing the distribution of features. The data had a slight class imbalance, with more patients surviving than dying.

Several sampling and modeling techniques were compared:

- Oversampling the minority class to balance the data
- Models like decision trees, random forests, logistic regression, SVM
- Validation with holdout and 5-fold cross-validation

Feature selection was done to find the most relevant variables. The top predictors were creatinine phosphokinase, age, and serum creatinine.

The best performing model was a Random Forest with SMOTE-NC oversampling and Holdout method. It achieved 74.5% in term of F1 score.

The Holdout and Kfold scheme shows the whole pipeline used during the experiments.
