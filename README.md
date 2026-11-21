# My Data Science & Machine Learning Portfolio

Welcome to my portfolio! This repository showcases my practical projects in machine learning, predictive modeling, and data analysis, built using Python.

---

## Projects Overview

### 1. Insurance Claims Charges Prediction
* **Description:** A regression project focused on predicting medical insurance charges based on demographic and health-related features (such as age, BMI, smoking status, and region).
* **Key Steps & Techniques:**
  * **Data Preprocessing & Cleaning:** Handled duplicates, detected and removed outliers using the IQR method, and encoded categorical variables (`drop_first=True`).
  * **Feature Selection & Scaling:** Applied RFECV (Recursive Feature Elimination with Cross-Validation) and feature standardization.
  * **Advanced Modeling:** Explored Linear Regression, Box-Cox transformation on the target variable to handle skewness, and K-Nearest Neighbors (KNN) Regressor with GridSearchCV.
* **Evaluation Metrics:** Evaluated models using MAE, MSE, RMSE, MAPE, and $R^2$ score on both training and test sets.
* **Tech Stack:** Python, Pandas, Scikit-Learn, Matplotlib, Seaborn

---

### 2. Disease Prediction (Breast Cancer Classification)
* **Description:** A binary classification project aimed at predicting the presence of disease (malignant vs. benign) using cellular characteristics.
* **Key Steps & Techniques:**
  * **Data Cleaning & Imputation:** Handled missing values (using median imputation) and removed duplicates.
  * **Data Balancing & Splitting:** Performed a 70/30 train-test split and data standardization.
  * **Modeling & Optimization:** Implemented and tuned multiple machine learning algorithms including K-Nearest Neighbors (KNN), Logistic Regression (with optimal threshold tuning using Youden's J statistic), Decision Trees (with cost-complexity pruning), Random Forest, and Support Vector Classifier (SVC) with PCA dimensionality reduction.
* **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, F2-score, and ROC-AUC curves.
* **Tech Stack:** Python, Pandas, Scikit-Learn, SciPy

