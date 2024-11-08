# Machine-Learning-with-Logistic-Regression

## Project Description

In this project, the goal is to predict which customers of a telecommunications company are likely to cancel their contracts. The objective is to identify potential churners and calculate their probability of leaving, enabling the company to implement targeted measures like promotional offers or discounts. This approach aims to retain customers and avoid revenue losses. It's crucial for the model to minimize unnecessary actions on customers who won’t churn, while also ensuring that no potential churners are overlooked. Additionally, the project seeks to identify the primary factors that contribute to customer churn.

Predicting customer churn is particularly relevant in the telecommunications industry, as market liberalization and technological innovations make it easy for customers to switch providers. Studies have shown that retaining existing customers is significantly more cost-effective than acquiring new ones.

Logistic regression is a well-suited algorithm for binary classification problems where the goal is to predict the probability of a customer leaving the company (1) or staying (0). Using independent variables such as contract duration, monthly charges, or services used, logistic regression can model a customer’s likelihood of churning.

## Data Used

- The Telco sutomer churn dataset for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data) and includes information about Services that each customer has signed up for, Customer account information and Demographic info about customers. Each row represents a customer, and each column contains an attribute. The dataset consists of 7,043 customer records, each with 20 features, along with data on whether the customer churned within the last month.

| Column number| Column name | Type | Description |
|:----------|:----------|:----------|:----------|
|0   | customerID   | Categorical   | customerID   |
|1   | gender   | Categorical   | Whether the customer is a male or a female   |
|2   | SeniorCitizen   | Categorical   | Whether the customer is a senior citizen or not (1, 0)   |
|3   | Partner   | Categorical   | Whether the customer has a partner or not (Yes, No)   |
|4   | Dependents   | Categorical   | Whether the customer has dependents or not (Yes, No)   |
|5   | tenure   | Numerical   | Number of months the customer has stayed with the company   |
|6   | PhoneService   | Categorical   | Whether the customer has a phone service or not (Yes, No)   |
|7   | MultipleLines   | Categorical   | Whether the customer has multiple lines or not (Yes, No, No phone service)   |
|8   | InternetService   | Categorical   | Customer’s internet service provider (DSL, Fiber optic, No)   |
|9   | OnlineSecurity   | Categorical   | Whether the customer has online security or not (Yes, No, No internet service)   |
|10   | OnlineBackup   | Categorical   | Whether the customer has online backup or not (Yes, No, No internet service)   |
|11   | DeviceProtection   | Categorical   | Whether the customer has device protection or not (Yes, No, No internet service)   |
|12   | TechSupport   | Categorical   | Whether the customer has tech support or not (Yes, No, No internet service)   |
|13   | StreamingTV   | Categorical   | Whether the customer has streaming TV or not (Yes, No, No internet service)   |
|14   | StreamingMovies   | Categorical   | Whether the customer has streaming movies or not (Yes, No, No internet service)   |
|15   | Contract   | Categorical   | The contract term of the customer (Month-to-month, One year, Two year)   |
|16   | PaperlessBilling   | Categorical   | Whether the customer has paperless billing or not (Yes, No)   |
|17   | PaymentMethod   | Categorical   | The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card    |
|18   | MonthlyCharges   | Numerical   | The amount charged to the customer monthly   |
|19   | TotalCharges   | Numerical   | The total amount charged to the customer   |
|20   | Churn   | Categorical   | Whether the customer churned or not (Yes or No)   |

## Objectives

- Analyze the dataset and understand its features.
- Clean and preprocess the data for modeling.
- Perform feature engineering to enhance predictive power.
- Apply logistic regression to classify customer churn.
- Optimize logistic regression model parameters.
- Interpret the model’s results and insights.

## License

This project includes data originally provided by IBM, available in their [GitHub repository](https://github.com/IBM/telco-customer-churn-on-icp4d). The dataset is used here under the terms of the [Apache License 2.0](./LICENSE) provided in the original repository.
