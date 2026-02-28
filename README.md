COVID-19 Urgent Hospitalization Risk Modeling

Comparative Policy-Oriented Data Analysis

Capstone Project – HarvardX CS109x: Introduction to Data Science with Python

Project Overview

This project analyzes patient-level COVID-19 data to identify factors associated with urgent hospitalization outcomes and to evaluate predictive classification models under different healthcare policy constraints.

Rather than optimizing purely for accuracy, this analysis demonstrates how model evaluation and decision thresholds must adapt to real-world public health objectives and resource limitations.

Objectives

Identify demographic and symptom-related predictors of urgent COVID-19 hospitalization

Compare classification models (Logistic Regression vs. K-Nearest Neighbors)

Evaluate model performance using ROC curves and AUC metrics

Simulate policy-oriented deployment scenarios under different national healthcare priorities

Demonstrate how model selection depends on context, not accuracy alone

Dataset & Methodology
Data Processing

Data cleaning and preprocessing

KNN-based imputation for missing values

Feature selection and encoding

Train/test split for out-of-sample validation

Exploratory Data Analysis (EDA)

Age distribution analysis

Symptom frequency patterns

Hospitalization outcome breakdown

Correlation exploration

Modeling Approach

Logistic Regression (baseline interpretable model)

K-Nearest Neighbors (non-linear classifier)

ROC curve analysis

AUC comparison

Threshold sensitivity evaluation

Policy-Oriented Evaluation Scenarios

To illustrate real-world decision-making trade-offs, model performance was analyzed under three hypothetical healthcare contexts:

Brazil – Conservative Classification
Objective: Reduce false positives to avoid unnecessary public alarm and hospital overload.

Germany – High Sensitivity Strategy
Objective: Minimize false negatives to reduce fatal outcomes, prioritizing early intervention.

India – Resource-Constrained Triage
Objective: Optimize patient prioritization under limited hospital capacity.

These scenarios highlight that optimal thresholds and model choice vary depending on healthcare objectives, risk tolerance, and resource availability.

Key Findings

Age and symptom combinations are strong predictors of urgent hospitalization

KNN outperformed Logistic Regression in AUC, suggesting non-linear relationships

Decision thresholds significantly impact classification trade-offs

Model deployment must align with policy goals and operational constraints

Tools & Technologies

Python (pandas, numpy, scikit-learn)

Matplotlib and Seaborn

Jupyter Notebook

ROC and AUC evaluation metrics

Future Improvements

Incorporate cross-validation for model robustness

Explore tree-based models (Random Forest, Gradient Boosting)

Conduct feature importance analysis for improved interpretability

Apply calibration techniques for probability adjustment

Author

Michelle Regalado Betancourtt
Economist | Data Analytics & Predictive Modeling
Focused on applying machine learning to economic and public policy challenges