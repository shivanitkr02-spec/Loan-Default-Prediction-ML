# Loan Default Prediction using Machine Learning

## Project Overview
This project focuses on building an end-to-end credit risk analytics pipeline to predict loan default probability using historical borrower data.  
The objective is to support data-driven credit assessment and improve loan approval and risk management decisions in financial institutions.

---

## Dataset Description
- Structured credit dataset with **20+ financial and demographic features**
- Key variables include loan duration, credit amount, employment status, savings behavior, age, and housing
- A proxy **default indicator** was engineered using business logic based on credit exposure and loan tenure

---

## Approach & Methodology
- Performed data cleaning and exploratory data analysis (EDA) to identify key default risk drivers
- Applied categorical encoding and feature standardization for model readiness
- Built and compared multiple classification models to balance interpretability and predictive performance

---

## Models Evaluated
- Logistic Regression (baseline & interpretable model)
- Decision Tree
- Random Forest
- Gradient Boosting

Models were evaluated using **ROC-AUC, confusion matrix, and recall for default class**, with emphasis on minimizing missed defaulters.

---

## Key Results
- Achieved **ROC-AUC > 0.75** on test data
- Improved identification of high-risk borrowers by **~20–25% recall uplift** through threshold optimization
- Identified major risk drivers such as **loan duration, credit amount, employment stability, and savings status**

---

## Business Impact
- Enables early identification of high-risk loan applicants
- Supports risk-based loan approval and pricing decisions
- Demonstrates how machine learning can reduce potential credit losses and improve portfolio quality

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
m

