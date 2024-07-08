# Credit-Risk-Modeling

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
[Alt Text](https://www.github.com/Sayuksh/CREDIT-RISK-MODELING/Female_Income_vs_Age.png)
[Alt Text](https://www.github.com/Sayuksh/CREDIT-RISK-MODELING/Male_Income_vs_Age.png)

### Modeling
#### Decision Tree
- accuracy: 0.85
- recall: 0.85
#### Random Forest
- accuracy: 0.87
- recall: 0.87
#### XGBoost
- accuracy: 0.60
- recall: 0.61
#### Linear Discriminant Analysis
- accuracy: 0.47
- recall: 0.42

Based on the metrics above and the calibration curve, Random Forest has a stong predictive performance.
[Alt Text](https://www.github.com/Sayuksh/CREDIT-RISK-MODELING/Graphical_representation.png)

### Credit Strategy
Develop a business strategy by setting various acceptance rate to maximize the estimate portfolio value
