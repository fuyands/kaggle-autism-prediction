Kaggle competition on predicting autism based on 21 features. Most of them are categorical. In this notebook, I explored dataset and found:
- No issue of missing values
- Most categorical features are binary
- Correlation matrix show a few features A3_Score and results have strong linear correlation to labels

I applied the following classifier to train the model:
- RidgeClassifier
- GaussianProcessClassifier
- RandomForestClassifier
- XGBoostClassifier

XGBoostClassifier shows the best private test score among these models.
