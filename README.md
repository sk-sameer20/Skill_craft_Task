# SCT_DS_Task03 - Decision Tree Classifier

## Objective
Build a Decision Tree Classifier to predict whether a customer will purchase a product or service based on demographic and behavioral data.

## Dataset
Bank Marketing Dataset from the UCI Machine Learning Repository.

The dataset contains customer information such as:
- Age
- Job
- Marital Status
- Education
- Balance
- Housing Loan
- Personal Loan
- Contact Type
- Campaign Information
- Previous Marketing Outcomes

Target Variable:
- y (Yes/No) – Whether the customer subscribed to the term deposit.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Steps Performed

1. Data Loading
2. Data Cleaning and Preprocessing
3. Encoding Categorical Features
4. Train-Test Split
5. Building Decision Tree Classifier
6. Model Training
7. Prediction
8. Model Evaluation
9. Decision Tree Visualization
10. Feature Importance Analysis

## Model
Decision Tree Classifier

Parameters Used:

```python
DecisionTreeClassifier(
    criterion='entropy',
    max_depth=5,
    random_state=42
)
```

## Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

## Output Files

- Task-3.ipynb
- decision_tree_bank_marketing.png
- bank_confusion_matrix.png
- bank_feature_importance.png

## Results
The Decision Tree model was trained to predict customer subscription behavior and evaluated using classification metrics. Feature importance analysis was performed to identify the most influential variables affecting customer decisions.

## Author
sameer
