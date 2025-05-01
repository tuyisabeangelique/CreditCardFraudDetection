<h1>Credit Card Fraud Detection</h1>

This project demonstrates the implementation and evaluation of machine learning models to detect fraudulent credit card transactions using Python, Scikit-learn, and Matplotlib. The dataset used for this project is sourced from Kaggle.

**Project Overview**

Credit card fraud detection is a critical task in ensuring secure and trustworthy financial transactions. In this project, we utilized machine learning models to classify transactions as either legitimate or fraudulent. The project includes:

- Data preprocessing and exploratory data analysis (EDA).
- Training and evaluation of classification models.
- Visualization of results using confusion matrices and ROC curves.

**Dataset:**

The dataset used in this project is publicly available on Kaggle: [Credit Card Fraud Detection Dataset.](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) 

# Credit Card Fraud Detection

This project demonstrates the implementation and evaluation of a machine learning pipeline to detect fraudulent credit card transactions using Python, Scikit-learn, and Matplotlib. The dataset is sourced from [Kaggle’s Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## Project Overview

Credit card fraud detection is a high-stakes classification problem where legitimate transactions vastly outnumber fraudulent ones. This project explores how machine learning can be applied to imbalanced data to flag anomalies in financial systems — a challenge that has parallels in legal and investigative platforms.

The workflow includes:
- **Data preprocessing**: normalization and handling missing values
- **Class imbalance handling** using SMOTE (Synthetic Minority Oversampling Technique)
- **Model training**: Logistic Regression was used for interpretability and baseline performance
- **Evaluation**: ROC-AUC score, confusion matrix, and classification report
- **Visualization**: Class distribution, transaction amount histograms, ROC curves

## Tech Used
- Python (pandas, numpy)
- Scikit-learn (modeling and metrics)
- imbalanced-learn (SMOTE)
- Matplotlib (visualizations)
- Jupyter Notebook

## Results Summary
- AUC Score: ~0.95
- Balanced precision and recall, showing effectiveness at detecting fraud while minimizing false positives
- ROC and confusion matrix visualizations for model transparency

## Why This Project Matters
This project highlights my ability to:
- Work with real-world datasets and class imbalance
- Build, train, and evaluate ML pipelines
- Communicate technical results clearly and visually
- Understand and address risks tied to false positives/negatives — critical in fields like fraud and legal tech

## How to Run
Open the `FraudDetection.ipynb` Jupyter Notebook and run each cell in order. No custom packages required beyond those listed above.

---

Submitted by: Angelique Tuyisabe
