# Wine Quality Prediction (Machine Learning)

## Project Overview
This project applies machine learning techniques to predict wine quality based on physicochemical properties such as acidity, alcohol content, sulphates, and pH. The goal is to classify wines into **Good** or **Bad** quality categories to support data-driven quality assessment.

## Problem Statement
Wine quality evaluation is often subjective and relies on expert tasting. This project aims to build a predictive model that uses measurable chemical features to objectively assess wine quality.

## Dataset
The dataset used in this project is the **UCI Wine Quality Dataset**, which contains red and white wine samples with physicochemical attributes and quality scores.

## Approach
The project follows a structured machine learning pipeline:
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Binary classification (Good vs Bad wine)
- Model training on unbalanced data
- Model training using SMOTE-balanced data
- Model evaluation using F1-macro, accuracy, and ROC-AUC

## Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  

## Tools & Technologies
- Python
- pandas, numpy
- scikit-learn
- imbalanced-learn (SMOTE)
- matplotlib, seaborn
- Jupyter Notebook

## Key Results

- Wine quality was framed as a binary classification problem:
  - **Good wine:** quality ≥ 7
  - **Bad wine:** quality ≤ 6
- Several models were evaluated, including Logistic Regression, Decision Tree, and Random Forest.
- The **Random Forest model trained on SMOTE-balanced data** achieved the best overall performance:
  - **Macro F1-score ≈ 0.70**
  - Improved recall for high-quality wines compared to baseline models.

## Report
A detailed description of the methodology, experiments, and results is available here:

- 📄 **Final Project Report:** `reports/20251027_WineQualityPrediction_StephenEmmanuel.pdf`

