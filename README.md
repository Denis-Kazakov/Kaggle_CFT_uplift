# Kaggle Uplift contest

## SHIFT project. Center for Financial Technologies

https://www.kaggle.com/competitions/uplift-shift-23

This branch is an attempt to use purchase history by flattening it. Before flattening, I aggregate purchase data by periods, trying different lengths of those periods to see which one works best. Otherwise, I use the standard approach: sklift with xgboost.

Notebooks:
- EDA
- adversarial_validation: checking that all data splits are properly stratified
- numbered notebooks: data preparation with a given number of periods and uplift prediction with data aggregated by these periods

