<img width="312" alt="2" src="https://github.com/user-attachments/assets/ecf0eb2e-1554-42a1-85a2-16db0002fb79" />
<br>
<img width="393" alt="1" src="https://github.com/user-attachments/assets/b487ae49-d085-4aaf-8458-541507963f38" />

# Credit Risk Classification

## Overview

This project focuses on building a supervised machine learning model to classify loans as either **healthy (Class 0)** or **high-risk (Class 1)**. The analysis is conducted using a dataset of 77,500 loan entries, incorporating financial attributes such as loan size, interest rate, borrower income, debt-to-income ratio, and credit history metrics.

We use **Logistic Regression** from `scikit-learn` as a binary classifier to make predictions, evaluate model performance, and gain insights into credit risk.

---

## Project Objectives

- Predict whether a loan is **healthy** or **high-risk**
- Train and evaluate a logistic regression classifier
- Analyze model performance using accuracy, precision, and recall
- Address dataset imbalance issues and identify areas of improvement

---

## Dataset Description

The dataset includes the following features:

- `loan_size`
- `interest_rate`
- `borrower_income`
- `debt_to_income_ratio`
- `number_of_accounts`
- `derogatory_marks`
- `total_debt`

**Target variable:**  
- `loan_status` — 0 for healthy, 1 for high-risk

---

## Methodology

1. **Data Preprocessing**
   - Load and clean the dataset
   - Separate features and target variable
   - Split data into training and testing sets

2. **Model Development**
   - Build a Logistic Regression model
   - Fit the model on training data
   - Predict on test data

3. **Model Evaluation**
   - Calculate accuracy, precision, and recall
   - Analyze performance for both classes
   - Discuss dataset imbalance and limitations

---

## Results

| Metric             | Healthy Loan (Class 0) | High-Risk Loan (Class 1) |
|--------------------|------------------------|---------------------------|
| Precision          | 1.00                   | 0.85                      |
| Recall             | 0.99                   | 0.91                      |
| Overall Accuracy   | 0.99                   | -                         |

> Note: The model performs exceptionally well on healthy loans but has slightly lower performance on high-risk loans due to class imbalance.

---

## Installation & Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/credit-risk-classification.git
cd credit-risk-classification
