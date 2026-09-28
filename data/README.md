## Data Overview
This directory contains the synthetic transaction dataset used in the Transactional Fraud Detection proof of concept built with Amazon SageMaker.

## Data Source
The raw dataset was generated with AI assistance for educational and portfolio purposes. It does not contain real customer transaction records.

**File:** `raw_transaction_data.csv`

## Dataset Description
The dataset contains transaction-related attributes intended to support the exploration of transaction patterns and fraud classification. The raw dataset includes features such as:
- Transaction amount
- Transaction hour
- Distance from home
- Account age
- Previous transaction count
- Country
- Device type
- Payment method

## Data Preparation
The raw dataset was imported into Amazon SageMaker Data Wrangler for data preparation. The workflow included handling missing values, removing duplicate records, and preparing transaction features for model building.
