## Risky Business

### In this assignment, a client has asked that we help them predict credit credit risk using Machine Learning Techniques. Imbalanced-learn & Scikit-learn libraries were used to build & evaluate models.

### We were provided with the stater code & data for 2 notebooks:

* credit_risk_resampling.ipynb
* credit_risk_ensemble.ipynb
* lending_data.csv
* LoanStats_2019q1.csv

### In the 'credit_risk_resampling' notebook:

* Imported the imbalanced learn library to resample the LendingClub data and built and evaluated logistic regression classifiers using the resampled data.

* Split the data into Training & Testing sets. The Pandas 'X.describe()' function computes and displays the: count, mean, std, min, 25%, 50%, 75%, max by analyzing dataset. From the values, we learn that the loan is low risk.

* A Simple Regression Report was run to determine the average of risks.

* Oversampling-- compared 2 oversampling algorithims:
Naive Random Oversampling
&
SMOTE.

* Undersampled the data using Cluster Centroids algoritihm.

* Under/oversampled using a combo SMOTEENN algoritihm to determine if the algorithim results in the the BEST performance compared to the other sampling algorithims used. We determined the best of all the models used.


### In the 'credit_risk_ensemble' notebook:

* Trained & compared 'Balanced Random Forest Classifier' & the 'Easy Ensemble Classifier' to predict loan risk and evaluate each model.

* Read the data from 'LoanStats_2019Q1.csv'.
Split the data into training & testing sets. 

* From the 2 models:
'Standard Scaler & 'sklearn.preprocessing' determine which one has the best balanced accuracy score, best recall score, best geometric mean score & the top 3 features





