# COVID-19 Comparative Data Analysis

Capstone project for HarvardX CS109x – Introduction to Data Science with Python.

This project analyzes patient-level COVID-19 data to identify factors associated with urgent
hospitalization outcomes and to evaluate predictive models under different policy and resource
constraints.

## Objective
To explore demographic and symptom-related patterns linked to urgent COVID-19 cases and to assess
the performance of supervised classification models using context-dependent evaluation criteria.

## Data & Methods
- Data cleaning and preprocessing, including KNN-based imputation
- Exploratory data analysis (EDA) of demographic and symptom variables
- Supervised learning models (Logistic Regression and K-Nearest Neighbors)
- Model evaluation using ROC curves and AUC metrics
- Policy-oriented scenario analysis reflecting different healthcare objectives

## Policy-Oriented Scenarios
The project evaluates model performance under three hypothetical policy contexts:
- Brazil: Conservative classification to limit public alarm
- Germany: High sensitivity to minimize fatal outcomes
- India: Resource-constrained triage under limited hospital capacity

These scenarios demonstrate how optimal model selection and decision thresholds depend on
real-world constraints rather than accuracy alone.

## Key Findings
- Age and symptom combinations are relevant predictors of urgent hospitalization
- KNN outperformed Logistic Regression, suggesting non-linear relationships in the data
- Model evaluation and deployment must be aligned with policy objectives and resource availability

## Tools & Technologies
- Python (pandas, numpy, scikit-learn)
- Matplotlib, Seaborn
- Jupyter Notebook

## Author
Michelle Regalado Betancourtt  
Economist 

