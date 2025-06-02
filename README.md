# 🧪 Handling Class Imbalance in Machine Learning

This repository provides a hands-on guide for addressing the **class imbalance problem** using various resampling techniques and evaluation metrics. The content is structured as an interactive tutorial notebook, originally prepared for the **Data Science Africa Summer School 2025**.

## 📌 Problem Overview

In many real-world applications—like fraud detection, medical diagnosis, or rare event modeling—datasets are **imbalanced**, meaning one class significantly outnumbers others.

For example, a classifier may achieve 95% accuracy by always predicting the majority class, while completely failing to identify the minority class (which may be the class of interest). This makes accuracy **misleading** in such cases.

## 🎯 What You'll Learn

- How to **detect and visualize class imbalance**
- How to apply **resampling techniques** like:
  - SMOTE (Synthetic Minority Over-sampling)
  - ADASYN
  - RandomOverSampler / RandomUnderSampler
  - Tomek Links
  - Edited Nearest Neighbours (ENN)
  - SMOTE-ENN and SMOTE-Tomek
- Evaluate model performance with **fair metrics**:
  - F1-score
  - Balanced Accuracy
  - Geometric Mean (G-Mean)
  - Index Balanced Accuracy (IBA)
- Visualize the effects of resampling using **PCA plots**
- Use **interactive widgets** to explore sampling effects dynamically

## 📂 Folder Structure

