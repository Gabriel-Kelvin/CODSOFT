# Customer Churn Prediction

This project aims to predict customer churn using machine learning techniques. Customer churn refers to the loss of customers or clients. By predicting which customers are likely to leave, businesses can take proactive measures to retain them.

## Overview
Customer churn prediction involves analyzing customer data to identify patterns that indicate whether a customer is likely to leave. This project uses various machine learning algorithms to build and evaluate models for predicting churn.

## Dataset
The dataset used for this project is the "Churn_Modelling.csv" file. It contains customer information such as:
- CustomerID
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
- Exited (whether the customer has churned)

## Installation
To run this project, you need to have Python installed along with the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn shap
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
   ```

2. Open the Jupyter notebook:
   ```bash
   jupyter notebook Customer_Churn_Prediction.ipynb
   ```

3. Run the notebook cells to execute the code step by step.

## Model Training
The following steps are performed for model training:
1. **Data Loading**: Load the dataset using Pandas.
2. **Data Cleaning**: Handle missing values, encode categorical variables, and scale numerical features.
3. **Train-Test Split**: Split the data into training and testing sets.
4. **Model Training**: Train various machine learning models including Logistic Regression, Random Forest, and Gradient Boosting.
5. **Feature Importance**: Use SHAP values to understand feature importance.

## Evaluation
The models are evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score

## Results
The performance of each model is compared based on the evaluation metrics. The model with the best performance is selected for predicting customer churn.
