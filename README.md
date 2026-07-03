# Customer Churn Prediction

## Project Overview

This project uses Machine Learning to predict whether a telecom customer is likely to cancel their subscription (churn).

The goal is to help businesses identify customers who are at high risk of leaving so they can take action to retain them.

---

## Business Problem

Customer churn leads to revenue loss for subscription-based businesses.

Instead of waiting until customers leave, the company can use machine learning to predict customers who are likely to churn and offer targeted retention strategies.

---

## Dataset

IBM Telco Customer Churn Dataset

The dataset contains information such as:

- Customer demographics
- Contract type
- Internet service
- Monthly charges
- Total charges
- Tenure
- Payment method
- Churn status

---

## Project Workflow

1. Business Understanding
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Feature Engineering
5. Train/Test Split
6. Logistic Regression
7. Model Evaluation
8. Random Forest
9. Model Comparison

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Models Used

### Logistic Regression

Used as the baseline classification model.

### Random Forest

Used to compare performance with Logistic Regression.

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score

Special attention was given to Recall because identifying customers who are likely to churn is more important than simply achieving high accuracy.

---

## Results

### Logistic Regression

Accuracy: 78.82%

### Random Forest

Accuracy: 77.75%

For this dataset, Logistic Regression slightly outperformed Random Forest and achieved better Recall for identifying customers who were likely to churn.

---

## How to Run

Clone the repository

```bash
git clone <https://github.com/Munezero26200/1st-ML-project.git>
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature importance analysis
- ROC Curve and AUC
- Handling class imbalance using SMOTE
- Model deployment with Flask or FastAPI

---

## Author

Aline Munezero