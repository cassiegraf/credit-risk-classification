<h2>
Credit Analysis Report
<h2>

<h4>
The purpose of the analysis is to determine if credit applicants will be 'healthy' or 'high-risk' loan borrowers. 
<h4>

#### The machine learning model scores came back as follows for the Logistic Regression Model:
* #### 99% accuracy in predicting whether a borrower will be high-risk or not
* #### 100% precision when predicting 'healthy' borrowers
* #### 99% recall when predicting 'healthy' borrowers 
* #### 85% precision when predicting 'high-risk' borrowers
* #### 91% recall when predictin 'high-risk' borrowers

#### The Logistic Regression Model is very good when looking at 'healthy' borrowers, however, the confidence levels drop significantly when looking at 'high-risk' borrowers.


#### The machine learning model scores came back as follows for the Logistic Regrssion Model with Resampled Data:
* #### 99% accuracy in predicting whether a borrow will be high-risk or not
* #### 100% precision when predicting 'healthy' borrowers
* #### 99% recall when predicting 'healthy' borrowers
* #### 84% precision when predicting 'high-risk' borrowers
* #### 99% recall when predicting 'high-risk' borrowers

#### The Logistic Regression Model with Resampled Data performs similarly to the Logistic Regression Model. However, this model has higher recall when predicting 'high-risk' borrowers.

#### I do recommend using this model as it provides 99% accruacy overall when predicting a 'healthy' vs 'high-risk' borrower. It could use some improvement on the precision of predicting 'high-risk' borrowers, which a lender would be concerned about.


#### used code from this link to help with the RandomOverSampler section: https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.RandomOverSampler.html
