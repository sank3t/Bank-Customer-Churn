## Predicting Bank Customer Churn

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sank3t/Bank-Customer-Churn/HEAD)

### Problem Statement
Which factors are causing the customer to close their bank account?

### Dataset

#### Data Source
The dataset is downloaded from [Kaggle](https://www.kaggle.com/shrutimechlearn/churn-modelling).

Thanks :slightly_smiling_face: to the Data Science community out there.

#### Data Dictionary

| Column          | Description                                                                              |
|:----------------|:-----------------------------------------------------------------------------------------|
| RowNumber       | Row Numbers from 1 to 10000                                                              |
| CustomerId      | Unique Ids for bank customer identification                                              |
| Surname         | Customer's last name                                                                     |
| CreditScore     | Credit score of the customer                                                             |
| Gender          | Male or Female                                                                           |
| Age             | Age of the customer                                                                      |
| Tenure          | Number of years for which the customer has been with the bank                            |
| Balance         | Bank balance of the customer                                                             |
| NumOfProducts   | Number of bank products the customer is utilising                                        |
| HasCrCard       | Binary Flag for whether the customer holds a credit card with the bank or not            |
| IsActiveMember  | Binary Flag for whether the customer is an active member with the bank or not            |
| EstimatedSalary | Estimated salary of the customer in Dollars                                              |
| Exited          | Binary flag 1 if the customer closed account with bank and 0 if the customer is retained |

#### Defining variable type

| Column          | Type          |
|:----------------|:--------------|
| CreditScore     | Discrete      |
| Gender          | Nominal       |
| Age             | Discrete      |
| Tenure          | Discrete      |
| Balance         | Continuous    |
| NumOfProducts   | Discrete      |
| HasCrCard       | Nominal       |
| IsActiveMember  | Nominal       |
| EstimatedSalary | Continuous    |

### Notebooks
* [EDA of the dataset](https://nbviewer.jupyter.org/github/sank3t/Bank-Customer-Churn/blob/master/EDA%20-%20Bank%20Customer%20Churn.ipynb) _*WIP_
