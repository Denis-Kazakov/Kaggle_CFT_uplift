# Kaggle Uplift contest

## SHIFT project. Center for Financial Technologies

https://www.kaggle.com/competitions/uplift-shift-23

This branch uses the standard approach: sklift library with various base estimators and different sets of features:
1. An original set of features: files with "all_features" in file names.
2. Added new features.
3. Ranked new features by importance and tried various sets from the 1st to n-the features.

XGBoost proved to be the best base estimator so far. The last notebook with best results is 12_...

Notebooks:
- EDA
- data_prep: data preparation
- baseline*: first attempts
- adversarial_validation: checking that all data splits are properly stratified
- numbered notebooks (01_..., etc.): various solutions

