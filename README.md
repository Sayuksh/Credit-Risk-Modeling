# CreditRiskModeling
### Introduction
Credit score cards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk.
 
Generally speaking, credit score cards are based on historical data. Once encountering large economic fluctuations. Past models may lose their original predictive power. Logistic model is a common method for credit scoring. Because Logistic is suitable for binary classification tasks and can calculate the coefficients of each feature. In order to facilitate understanding and operation, the score card will multiply the logistic regression coefficient by a certain value (such as 100) and round it.
 
At present, with the development of machine learning algorithms. More predictive methods such as Boosting, Random Forest, and Support Vector Machines have been introduced into credit card scoring. However, these methods often do not have good transparency. It may be difficult to provide customers and regulators with a reason for rejection or acceptance.

### Data
[Dataset](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction/data)



### Exploring and PreparingData
- Explore loan data set by cross tables and plots
- Impute the null values
- One-hot encode the non-numeric columns
- Scaling
- Deal with imbalanced data


![alt text](https://github.com/Sayuksh/Credit-Risk-Modeling/blob/main/Female_Income_vs_Age.png)
![alt text](https://github.com/Sayuksh/Credit-Risk-Modeling/blob/main/Male_Income_vs_Age.png)

### Modeling
#### Logistic Regression
- accuracy: 0.61
- recall: 0.61
#### Random Forest
- accuracy: 0.99
- recall: 0.99
#### XGBOOST
- accuracy: 0.99
- recall: 0.99


Based on the metrics above and the calibration curve, Random Forest has a stong predictive performance.


### Credit Strategy
Develop a business strategy by setting various acceptance rate to maximize the estimate portfolio value
