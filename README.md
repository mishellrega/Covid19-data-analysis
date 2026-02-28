# COVID-19 Urgent Hospitalization Risk Modeling
# Comparative Policy-Oriented Data Analysis
# Capstone Project — HarvardX CS109x: Introduction to Data Science with Python

# Project Overview

This project analyzes patient-level COVID-19 data to identify factors associated with urgent hospitalization outcomes and to evaluate predictive classification models under different healthcare policy constraints.

Rather than optimizing purely for accuracy, this analysis demonstrates how model evaluation and decision thresholds must adapt to real-world public health objectives and resource limitations.

# Objectives

Identify demographic and symptom-related predictors of urgent hospitalization

Compare classification models: Logistic Regression vs. K-Nearest Neighbors

Evaluate performance using ROC curves and AUC metrics

Simulate policy-oriented deployment scenarios

Show how optimal model selection depends on context — not accuracy alone

# 1. Dataset & Methodology
# Data Processing

Data cleaning and preprocessing

KNN-based imputation for missing values

Feature encoding

Train/test split

# 2 Exploratory Data Analysis (EDA)

Age distribution analysis

Symptom frequency patterns

Hospitalization outcome breakdown

Correlation exploration

# Modeling

Logistic Regression (interpretable baseline model)

K-Nearest Neighbors (non-linear classifier)

ROC curve analysis

AUC comparison

Threshold sensitivity analysis

# 3 Policy-Oriented Scenarios

To illustrate real-world trade-offs, model performance was evaluated under three hypothetical healthcare contexts:

🇧🇷 Brazil — Conservative Classification
Reduce false positives to avoid unnecessary hospital overload.

🇩🇪 Germany — High Sensitivity Strategy
Minimize false negatives to reduce fatal outcomes.

🇮🇳 India — Resource-Constrained Triage
Optimize patient prioritization under limited hospital capacity.

These scenarios highlight that model deployment must align with policy goals and operational constraints.

# Key Findings

Age and symptom combinations are strong predictors of urgent hospitalization

KNN achieved higher AUC, suggesting non-linear relationships

Threshold selection significantly impacts classification trade-offs

Model performance must be evaluated within policy context

# Tools & Technologies

Python (pandas, numpy, scikit-learn)

Matplotlib & Seaborn

Jupyter Notebook

ROC/AUC evaluation metrics

# Future Improvements

Apply cross-validation for stronger robustness

Explore tree-based models (Random Forest, Gradient Boosting)

Perform feature importance analysis

Add probability calibration

# Author

Michelle Regalado Betancourtt
Economist | Data Analytics & Predictive Modeling
Focused on applying machine learning to economic and public policy challenges
