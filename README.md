# Bankruptcy Prediction
Comparison of various classification algorithms that classify whether a company “will soon go bankrupt” or “will not go bankrupt”, based on their financial ratios.

**DATASET**
Link: https://archive.ics.uci.edu/ml/datasets/Taiwanese+Bankruptcy+Prediction#

1) Dimensions: 96 attributes (95 features + 1 label), 6819 instances 
2) Features: Financial ratios like Quick Ratio, Current Ratio, Equity to Liability, etc.
3) Label: ‘Bankrupt?’ (1 or 0 – 1 being yes, 0 being no)
4) Format: CSV file
5) No missing data
6) Attribute characteristics: Numerical
7) Class imbalanced


**OVERVIEW:**
1) For processing the data: outlier removal, feature selection, logarithmic transformation to remove skew, and randomized search cross validation with SMOTE.

2) The classification algorithms being compared are Logistic Regression, Random Forest, XGBoost and CatBoost Classifications after hyperparameter tuning.


**WEIGHTED METRICS OUTPUT:**
1) Without feature selection

![image](https://user-images.githubusercontent.com/67577967/137084735-032ec83b-1347-470e-a050-94625e10ff96.png)
![image](https://user-images.githubusercontent.com/67577967/137084853-4acb11e4-c38d-448f-bb83-2c08236f9fc6.png)


2) After Feature selection

![image](https://user-images.githubusercontent.com/67577967/137084923-642ebfb6-bfef-406e-86aa-dc26f133528f.png)
![image](https://user-images.githubusercontent.com/67577967/137085002-8ef1408a-a009-4899-ace0-ff682c331dd6.png)




