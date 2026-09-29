# Data Preparation

## Tool
Amazon SageMaker Data Wrangler

## Transformation Workflow
The Data Wrangler flow applies the following transformations to prepare transaction data for model building.

1. **Data type configuration** — Configured data types for the dataset.
2. **Data quality analysis** — Generated data quality and insights reports to inspect the dataset.
3. **Duplicate removal** — Removed duplicate records.
4. **Column removal** — Applied two column-removal steps to exclude selected columns.
5. **Missing-value handling** — Removed rows containing missing values.
6. **Feature engineering** — Applied four custom formula transformations to derive additional transaction-related features.

## Feature Engineering
Custom formulas were used to create derived features from transaction attributes. These included combinations of transaction distance, transaction time, account age, and previous transaction activity.
The derived features were intended to help the classification workflow explore relationships between transaction characteristics and the target variable.

## Output
The prepared dataset was used in Amazon SageMaker Canvas to build a binary classification model with `is_fraud` as the target column.

## Notes
This workflow demonstrates data preparation and feature engineering on synthetic transaction data. The usefulness of derived features and their ability to generalize to real-world fraud patterns require further evaluation.
