# Kaggle Uplift contest

## SHIFT project. Center for Financial Technologies

https://www.kaggle.com/competitions/uplift-shift-23

This branch is an attempt to leverage neural networks to use time-dependent data (purchase history). 

Time dependent and time-independent data have different dimensions so I used the functional API of keras.

The sklift library was not used as it requires base estimators with sklearn API. I used manual class transformation instead.

The first attempt was not successful: validation roc_auc ~ 0.5, without improvement during training.

Notebooks:
- data_prep: data preparation
- adversarial_validation: checking various splits for proper stratification
- 01_deep_learn: model training




