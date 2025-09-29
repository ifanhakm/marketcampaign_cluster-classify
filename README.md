# Marketing Campaign Segmentation & Classification

This project is part of my journey exploring **Machine Learning**, developed as a submission for **Dicoding**. I explored both **clustering** and **classification** techniques using a real-world marketing campaign dataset.

---

## Overview

The objective of this project was to:
- Understand customer segmentation using **clustering** techniques.
- Classify customers into predefined clusters using **classification**.
- Explore the power of **feature reduction** and **parameter tuning** to improve performance.

---

## Methodology

### 1. Exploratory Data Analysis (EDA)
- Conducted advanced **data cleaning**.
- Visualized correlations using **heatmaps**.
- Detected outliers and missing values.

### 2. Clustering
- Performed **unsupervised learning** to discover customer segments.
- Compared performance of:
  - ✅ K-Means (Accuracy: 26%) ((bruh))
  - ✅ DBScan (Accuracy: 64%)

### 3. Classification
- Applied **Random Forest Classifier** based on cluster labels.
- Used **GridSearchCV** for hyperparameter tuning.
- Implemented **PCA (Principal Component Analysis)** for feature reduction.
- Achieved **final accuracy: 94%** after tuning.

---

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- GridSearchCV, PCA

---

## Result Highlights
- Unsupervised segmentation produced meaningful customer groups.
- Classification model showed high performance in identifying these groups post-clustering.
- Demonstrated end-to-end pipeline: **EDA → Clustering → Classification → Tuning**.
