# PROJECT - CHURN PREDICTION

Churn prediction for a bank-provided dataset. Source: Kaggle

## DATASET ANALYSIS
Rows:
- RowNumber
- CustomerId
- Surname
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited

### COMMENTS
1. Credit score can have an effect on customer churn;  
higher credit score --> less likely to leave bank
2. Geography, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary are expected to play a role
3. Gender may be explored as a feature
4. Exited is the output
5. People with a credit card are less likely to leave the bank.
6. IsActiveMember — active customers are less likely to leave the bank.
7. EstimatedSalary — as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.