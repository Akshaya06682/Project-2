# AI-Powered Credit Card Fraud Detection

This project builds an AI system to detect fraudulent credit card transactions using machine learning.

## Table of Contents

- [Problem Statement](#problem-statement)  
- [Abstract](#abstract)  
- [System Requirements](#system-requirements)  
- [Objectives](#objectives)  
- [Dataset Description](#dataset-description)  
- [Project Workflow](#project-workflow)  
- [Model Performance](#model-performance)  
- [Deployment](#deployment)  
- [Future Scope](#future-scope)  
- [Team Members](#team-members)  
- [How to Run](#how-to-run)

---

## Problem Statement

Detect fraudulent credit card transactions in real-time using machine learning to help financial institutions prevent losses.  
**Problem Type:** Classification

---

## Abstract

This project aims to build an AI-powered system that predicts the likelihood of a transaction being fraudulent. Using a dataset of anonymized transaction records, we apply data preprocessing, feature engineering, and machine learning techniques. We test multiple models and deploy the best-performing one on a Streamlit web app. The result is a tool that can help businesses reduce fraud-related losses.

---

## System Requirements

- **Hardware:** 4GB RAM, Intel i3 or better  
- **Software:** Python 3.8+, scikit-learn, pandas, numpy, matplotlib, seaborn  
- **IDE:** Jupyter Notebook, Colab, or VS Code

---

## Objectives

- Build a predictive model to classify transactions as fraudulent or not  
- Minimize false positives and false negatives  
- Provide an interactive web app for testing predictions

---

## Dataset Description

- **Source:** Kaggle (Credit Card Fraud Detection Dataset)  
- **Type:** Public  
- **Size:** ~284,807 transactions, 31 columns (V1-V28, Amount, Time, Class)  
- `Class` is the target variable: 0 = normal, 1 = fraud

---

## Project Workflow

1. Data Collection  
2. Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Model Building  
6. Model Evaluation  
7. Deployment

---

## Model Performance

- **Best Model:** Random Forest Classifier  
- **Accuracy:** ~99%  
- **AUC-ROC:** ~0.98  
- Includes confusion matrix, classification report, and ROC curve visualizations

---

## Deployment

- **Platform:** Streamlit Cloud  
- **Public Link:** [Add your deployed app link here]  
- **UI Screenshot:** [Add screenshot here]

---

## Future Scope

- Integrate real-time API for live transaction checks  
- Improve class imbalance handling with SMOTE or ensemble methods  
- Add a dashboard for live monitoring and alerting

---

## Team Members

| Name             | Role                           |
|------------------|--------------------------------|
| [Member 1 Name] | Data collection, preprocessing |
| [Member 2 Name] | Feature engineering, modeling  |
| [Member 3 Name] | Evaluation, deployment         |
| [Member 4 Name] | Documentation, presentation    |

---

## How to Run

1. Clone the repo:# Project-2
AI credit card
