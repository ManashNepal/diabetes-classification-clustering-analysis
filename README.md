# Diabetes Classification and Clustering Analysis

This repository contains a machine learning project focused on multi-class diabetes classification and unsupervised clustering analysis.

The dataset consists of clinical and biochemical features such as HbA1c, BMI, lipid profile parameters, urea and creatinine. The target variable includes three categories:

- **N** – Non-diabetic
- **P** – Predict-diabetic
- **Y** – Diabetic

---

## Project Overview

This project aims to:

- Build supervised classification models to predict diabetic status.
- Apply unsupervised clustering to analyze natural groupings in the dataset.
- Compare classification performance with clustering behavior.
- Interpret results and derive meaningful insights.

---

## Methods Used

### 1. Data Preprocessing

- Data cleaning and label correction
- Removal of identifier columns
- Standard scaling for numerical features
- One-hot encoding for categorical features
- Pipeline integration to prevent data leakage

### 2. Supervised Learning

Models implemented:

- Logistic Regression
- Random Forest

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Stratified Cross-Validation

Hyperparameter tuning was performed using GridSearchCV.

### 3. Unsupervised Learning

- KMeans clustering
- Elbow method for optimal k selection
- Silhouette score evaluation
- PCA visualization of clusters

---

## Repository Structure

- `Classification_Clustering_Assignment.ipynb` – Complete Jupyter notebook with implementation and analysis.
- `Classification_Clustering_Documentation.pdf` – Detailed project documentation.

---

## Conclusion

This project demonstrates an end-to-end machine learning workflow including preprocessing, modeling, validation, interpretation and comparison between supervised and unsupervised approaches. The results provide both strong predictive performance and meaningful clinical insights.
