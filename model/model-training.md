
# Model Building

## Tool
Amazon SageMaker Canvas

## Model Configuration

Model name: `Model_fraud_detect` 
Model type: Binary classification
Target column: `is_fraud` 
Build method: Quick build 
Dataset size: 4,950 rows
Number of columns: 6

## Target Classes
- `0` — Legitimate transaction
- `1` — Fraudulent transaction

## Model Building Process
1. Selected the prepared transaction dataset in SageMaker Canvas.
2. Configured `is_fraud` as the target column.
3. Selected the Quick build option to train the classification model.
4. Reviewed the model's reported performance in the Analyze section.

## Model Output
The model was configured to classify transactions into legitimate and fraudulent categories. The model evaluation results are documented separately from the model-building process.

## Limitations
The model was built using synthetic transaction data. Its results do not establish that it can reliably detect fraud in real financial transactions.
