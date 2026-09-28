## 1. Project overview
This project is a proof of concept exploring how AWS machine learning services can be used to prepare transaction data and build a binary classification model for potential fraud detection.

#### Disclaimer: The project uses a synthetic transaction dataset containing transaction amounts, transaction times, account characteristics, transaction history, device types, merchant categories, and payment methods.

Using Amazon SageMaker Data Wrangler,the dataset will be inspected, data quality wil be assessed, missing values and duplicate records will be handled, and the transaction features will be investigated. Based on this analysis,a criteria for potential fraud will be defined and a binary target variable named is_fraud will be created.

The project demonstrates data preparation, feature engineering, target creation, model training, and model evaluation within the AWS machine-learning workflow.

## 2. Problem Statement
Financial transactions can exhibit different characteristics, including unusual transaction amounts, transaction times, account histories, and transaction locations. Examining these characteristics can provide a basis for exploring potential transaction risk.

This project investigates how transaction attributes can be transformed into a binary classification dataset and used to train a machine-learning model that predicts whether a transaction meets a defined potential-fraud criterion.

Because the dataset is synthetic, the fraud criteria will be defined for this proof of concept rather than derived from confirmed financial fraud cases.

## 3. Objectives
- Assess the quality and structure of raw transaction data.
- Identify and handle missing values and duplicate records.
- Investigate transaction attributes and their potential relevance to fraud risk.
- Define transparent criteria for labeling potential fraud.
- Create an is_fraud binary target variable in SageMaker Data Wrangler.
- Prepare the dataset for machine-learning model training.
- Build a binary classification model using SageMaker Canvas.
- Evaluate the model using available classification metrics.
- Document the methodology, results, limitations, and opportunities for improvement.


