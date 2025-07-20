
# Prodigy Task 2 - Decision Tree Classifier for Purchase Prediction

This repository contains the implementation of a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. This project is part of my Data Science Internship at **Prodigy Infotech**.

## 📌 Task Objective

Build a machine learning model using the **Bank Marketing Dataset** (UCI) to predict if a customer will subscribe to a term deposit.

## 🔍 Dataset

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- Format: CSV
- Records: 4,500+
- Target column: `y` (yes/no)

## 🧠 Steps Performed

1. Data cleaning and encoding categorical features
2. Dropped the `duration` column to avoid data leakage
3. Split data into training and test sets (80/20)
4. Trained a Decision Tree Classifier using `scikit-learn`
5. Evaluated model performance using classification metrics
6. Visualized top 3 levels of the decision tree

## 📊 Model Performance

- **Accuracy:** ~81%
- **Best at predicting**: Non-purchase behavior
- **Needs improvement**: Class imbalance handling for positive cases

## 📦 Dependencies

- pandas
- scikit-learn
- matplotlib

Install them using:

```bash
pip install -r requirements.txt
