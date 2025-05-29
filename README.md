# Data Analytics & Machine Learning on Healthcare Data

The project involved comprehensive **data preparation**, **classification**, **regression**, and **clustering** techniques using Python, focused on healthcare data to uncover meaningful patterns and improve predictive accuracy.

---

## Project Overview

### 1. Data Preparation
- Handled missing data using imputation
- Detected and treated outliers using IQR method
- Label encoded categorical variables
- Balanced classes using **SMOTE**
- Standardised data for clustering models

### 2. Classification (Target: Stroke)
Applied 6 classifiers and compared performance using metrics like precision, recall, F1-score, AUC:
- Decision Tree  
- Naïve Bayes  
- K-Nearest Neighbour  
- Support Vector Machine  
- Logistic Regression  
- AdaBoost  

📌 Best Performer: **Naïve Bayes** (96.4% accuracy, AUC: 0.964)

### 3. Regression (Target: BMI)
Evaluated 4 regression models using MAE, MSE, RMSE, R²:
- Linear Regression  
- Decision Tree Regression  
- K-Nearest Neighbour Regression  
- Support Vector Regression  

📌 Best Performer: **KNN Regression** (MAE: 2.87, R²: 0.31)

### 4. Clustering
Unsupervised learning to explore health condition patterns:
- K-Means
- Hierarchical Clustering
- Gaussian Mixture Model (GMM)

📌 Insight: Clustering revealed weak but interesting associations between age, work type, BMI, glucose level and health outcomes.

---

## Technologies Used

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- SMOTE for class balancing
- Unsupervised learning models

---

## Skills Demonstrated

- End-to-end data analysis and modelling
- Model evaluation and comparison
- Feature engineering and class balancing
- Visualisation and interpretation of complex healthcare data

---

