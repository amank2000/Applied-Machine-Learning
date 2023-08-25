
# Bank Customer Churn Analysis and Prediction

## Overview

This project aims to analyze and predict customer churn for a bank. Customer churn refers to when customers or subscribers stop doing business with a company or service. Predicting churn allows businesses to take proactive measures to retain valuable customers.

## Dataset

The dataset contains various features about bank customers, including:
- Customer demographics (e.g., age, gender)
- Account details (e.g., balance, number of products)
- Activity metrics (e.g., credit score, is active member)
- And more...

The target variable indicates whether a customer left the bank (churned: 1) or continued to be a customer (not churned: 0).

## Steps in the Notebook

1. **Data Loading and Exploration:** Load the data and get a preliminary understanding of its structure and content.
2. **Data Processing:** Preprocess the data by handling missing values, dropping irrelevant features, and encoding categorical variables.
3. **Handling Imbalanced Data using SMOTE:** Address the class imbalance problem using the Synthetic Minority Oversampling Technique.
4. **Data Splitting and Feature Scaling:** Split the data into training and test sets and scale the features.
5. **Model Training and Evaluation:** Train multiple machine learning models and evaluate their performance using metrics like accuracy, precision, recall, and F1 score.
6. **Conclusion and Model Saving:** Draw conclusions based on the model evaluations and save the best-performing model for future use.

## Conclusion

After a thorough analysis, the XGBoost (XGB) emerged as the top-performing model in terms of accuracy. Meanwhile, the Random Forest (RF) model exhibited the highest precision. For the given problem, depending on the business need (i.e., whether to prioritize overall correct predictions or to be more precise in predicting positive cases), either of these models can be chosen.

---

*Note: For a detailed walkthrough, refer to the Jupyter Notebook.*
