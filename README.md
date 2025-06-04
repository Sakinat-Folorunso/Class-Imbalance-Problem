# 🧪 Handling Class Imbalance in Machine Learning

This repository provides a hands-on guide for addressing the **class imbalance problem** using various resampling techniques and evaluation metrics. The content is structured as an interactive tutorial notebook, originally prepared for the **Data Science Africa Summer School 2025**.

## 👩🏾‍🏫 Facilitator

**Dr. Sakinat Oluwabukonla Folorunso**  
Associate Professor of AI Systems and FAIR Data Science

Artificial Intelligent Sytems Research Group

Olabisi Onabanjo University, Ago-Iwoye, Nigeria

[Google Scholar](https://scholar.google.com/citations?user=ysoR2G0AAAAJ) | [GitHub](https://github.com/Sakinat-Folorunso) | [Website](https://sites.google.com/view/sakinatfolorunso/home) | [TRAIL](https://sites.google.com/view/ai-trail-oou/home)

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

## 🧠 Requirements

- Python ≥ 3.7
- `scikit-learn`, `imbalanced-learn`
- `matplotlib`, `seaborn`, `ipywidgets`
- Jupyter Notebook or Google Colab

Google Colab Link: https://drive.google.com/drive/folders/1RserzXDW1KC_f6We1mRkjXUHl6X1CPVw?usp=drive_link 


Let’s build machine learning models that are not just accurate — but fair, balanced, and useful.
