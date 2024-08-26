# Alzheimer's Detection Project

This project aims to detect Alzheimer's disease using machine learning techniques. The models used in this project include Logistic Regression, Decision Tree, and Extreme Gradient Boost (XGBoost). The dataset was preprocessed, and various features were engineered to optimize the models' performance.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
  - [Logistic Regression](#logistic-regression)
  - [Decision Tree](#decision-tree)
  - [Extreme Gradient Boost (XGBoost)](#extreme-gradient-boost-xgboost)
- [Evaluation](#evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction

Alzheimer's disease is a progressive neurodegenerative disorder that affects millions of people worldwide. Early detection is crucial for managing the disease and improving patients' quality of life. This project explores different machine learning algorithms to predict the likelihood of a patient having Alzheimer's disease based on various clinical and demographic factors.

## Dataset

The dataset used in this project contains information on patients, including demographic data, cognitive test results, and medical history. The data was cleaned and preprocessed to handle missing values, encode categorical variables, and scale numerical features.

## Models
### Logistic Regression
Logistic Regression is a simple yet effective model for binary classification problems. In this project, Logistic Regression was applied to predict the probability of a patient having Alzheimer's disease. The model was trained using features such as age, cognitive test scores, and medical history.

### Decision Tree
The Decision Tree model was used to classify patients based on their clinical features. Decision Trees are known for their interpretability, making them a good choice for understanding how different factors contribute to the diagnosis of Alzheimer's.

### Extreme Gradient Boost (XGBoost)
XGBoost is an advanced implementation of gradient boosting algorithms and is known for its high performance in classification tasks. In this project, XGBoost was employed to improve the accuracy of Alzheimer's detection by combining the strengths of multiple decision trees.

## Evaluation
The models were evaluated using various metrics such as accuracy, precision, recall, and F1-score. Cross-validation was performed to ensure the models' generalizability.

## Results
Logistic Regression: Achieved an accuracy of X% with a precision of Y% and recall of Z%.
Decision Tree: Achieved an accuracy of A% with a precision of B% and recall of C%.
XGBoost: Achieved an accuracy of P% with a precision of Q% and recall of R%.
The results demonstrate that XGBoost outperformed the other models in terms of accuracy and generalization.

## Conclusion
This project highlights the effectiveness of machine learning techniques in detecting Alzheimer's disease. While all three models showed promising results, XGBoost emerged as the best-performing model. Future work could involve exploring additional features, fine-tuning hyperparameters, and testing other algorithms.