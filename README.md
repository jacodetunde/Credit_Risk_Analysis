# Credit Risk Analysis
## Overview
Loans are an integral part of modern society. It presents opportunities and poses a serious challenge for banks. It creates revenues with interest rate generated, and other hand, people default payment, thus, makes a loss of revenues. However, machine learning can be used to analyze large datasets to predict risk and inform the decision to approve loan application or reject it.

Usually, banks traditionally rely on income, credit scores, and collateral assets to assess lending risk. The challenge is that many data can be left out, which could have aided the lending decisions. In this project, I used the credit card dataset from LendingClub, a peer-to-peer lending services company, for the analysis. 

I used Python and Scikit-learn libraries to build algorithms and predict credit risk. I finally evaluate the following machine learning models:
- Naive Random Oversampling
- SMOTE Oversampling
- Undersampling
- SMOTEENN
- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier.

I then compared their strengths and weaknesses to assess how well each models works to classify and predict the risks.
## Results
#### 1. Naive Random Oversampling models:
![naive1.png](naive1.png)
- the balanced accuracy score is 0.65
![naive2.png](naive2.png)
- The precision score for high risk is 0.01 while the precision score for low risk is 1.0. The recall score for high risk is 0.64 while low risk is 0.66

#### 2. SMOTE Oversampling model
- ![smote_bas.png](smote_bas.png)
- The balance accuracy score for this model is 0.65
![smote_prf.png](smote_prf.png)
- The precision score is 0.01 and 1.0 for high risk and low risk respectively. While the recall score is 0.64 and 0.66 for high risk and low risk respectively.
#### 3. Undersampling model
![undersampling_bac.png](undersampling_bac.png)
- the balanced accuracy score for this model is 0.52
![undersampling_prf.png](undersampling_prf.png)
- The precision score is 0.01 and 1.00 for high risk and low risk respectively. While the recall is 0.63 and 0.41 for high risk and low risk respectively
#### 4. SMOTEENN ( the combination of Over and Under Sampling) model
![smoteenn.png](smoteenn.png)
- From this mode, the balance accuracy score is 0.637, the precision score for high risk and low risk are 0.01 and 1.00 respectively. While the recall scores are 0.70 and 0.57 respectively. 
## Summary
