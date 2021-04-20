# Home Credit Default Risk

#### Competition Description
Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders.

Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.

##### Data
- application_{train|test}.csv : Main table, broken into two files for Train (with TARGET) and Test (without TARGET).
- bureau.csv : All client's previous credits provided by other financial institutions that were reported to Credit Bureau (for clients who have a loan in our sample).
- bureau_balance.csv : Monthly balances of previous credits in Credit Bureau.
- POS_CASH_balance.csv : Monthly balance snapshots of previous POS (point of sales) and cash loans that the applicant had with Home Credit.
- credit_card_balance.csv : Monthly balance snapshots of previous credit cards that the applicant has with Home Credit.
- previous_application.csv : All previous applications for Home Credit loans of clients who have loans in our sample.
- installments_payments.csv : Repayment history for the previously disbursed credits in Home Credit related to the loans in our sample.
- HomeCredit_columns_description.csv : This file contains descriptions for the columns in the various data files.
- sampleSubmission.csv : default form of files to submit.
- submission_1.csv, submission_2.csv, submission_3.csv, submission_4.csv : submission file I created.

##### Used libraries
- numpy
- pandas
- matplotlib
- seaborn
- calendar
- LabelEncoder
- simpleImputer
- PolynomialFeatures
- MinMaxScaler
- LogisticRegression
- RandomForestClassifier

##### Data Source
https://www.kaggle.com/c/home-credit-default-risk/data<br>

The data required for analysis is too large, so please bring it directly from the kaggle site.