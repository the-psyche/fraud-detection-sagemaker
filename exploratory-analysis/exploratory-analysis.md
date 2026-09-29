# Exploratory Data Analysis

## Objective
The exploratory analysis was performed on the raw synthetic transaction dataset to understand its structure, data quality, and feature characteristics before preprocessing and model development.

## Dataset Overview
<img width="1920" height="970" alt="Screenshot 2026-09-26 100439" src="https://github.com/user-attachments/assets/7bcda9cd-82f0-4b13-9f67-4dd11f4f031e" />

## Features
The dataset contains the following transaction attributes:
- `transaction_id`
- `transaction_amount`
- `transaction_hour`
- `distance_from_home_km`
- `account_age_days`
- `previous_transactions`
- `country`
- `device_type`
- `merchant_category`
- `payment_method`

## Feature Exploration

- Transaction Amount
The `transaction_amount` feature represents the monetary value of each transaction.

- Transaction Hour
`transaction_hour` represents the hour at which a transaction occurred, allowing transaction activity to be examined across the 24-hour period.

- Distance From Home
`distance_from_home_km` represents the distance between the transaction location and the customer's expected or registered location.

- Account Age
`account_age_days` represents the age of the account in days.

- Previous Transactions
`previous_transactions` represents the number of previous transactions associated with the account.

- Categorical Feature Exploration
The raw dataset also contains categorical transaction attributes:
- country
- device_type
- merchant_category
- payment_method

These features provide categorical information that can be used by the machine learning workflow after appropriate preparation.

Target Variable
The raw dataset analyzed here does not contain the is_fraud target column. The target variable was introduced or prepared during the subsequent modeling workflow and represents:

Value	Meaning
0	Legitimate transaction
1	Fraudulent transaction
