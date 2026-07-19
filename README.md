
# 🎓 Student Performance Prediction

A machine learning project that predicts students' final grades using demographic, social, and academic features.

The project demonstrates a complete end-to-end machine learning workflow using Scikit-learn, from data preprocessing to model evaluation and hyperparameter tuning.

---

# Project Overview

The objective of this project is to predict students' final exam scores (G3) based on various factors such as:

- Age
- Parents' education
- Study time
- Previous failures
- Alcohol consumption
- Family relationship
- Health
- Absences
- First period grade (G1)
- and many other categorical features

Several regression models were trained and compared to identify the best-performing model.

---

# Dataset

Dataset:
Student Performance Dataset (UCI Machine Learning Repository)

Target Variable:

G3 (Final Grade)

Features:

- Numerical Features
- Categorical Features
---

# Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Feature Selection
5. Data Preprocessing
   - StandardScaler
   - OneHotEncoder
   - ColumnTransformer
6. Pipeline Construction
7. Model Training
8. Model Comparison
9. Feature Importance Analysis
10. Correlation Analysis
11. Cross Validation
12. Hyperparameter Tuning using GridSearchCV
13. Final Model Evaluation

---

# Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors
- Support Vector Regressor (SVR)


---

# Data Preprocessing

The preprocessing pipeline includes:

- Missing value handling
- Standard scaling for numerical features
- One-Hot Encoding for categorical variables
- ColumnTransformer
- Scikit-learn Pipeline

This ensures that preprocessing and model training are executed consistently.

---

# Model Evaluation

Evaluation metrics:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

The models were compared using the same train/test split.

Cross Validation was also performed to evaluate model stability.

---

# Hyperparameter Tuning

Random Forest hyperparameters were optimized using:

- GridSearchCV
- 5-Fold Cross Validation

Optimized parameters include:

- n_estimators
- max_depth
- min_samples_split
- min_samples_leaf

---

# Feature Importance

Feature importance analysis was performed using Random Forest.

The most influential features include:

- G1 (First Period Grade)
- Absences
- Failures
- Age
- Study Time


---

# Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Joblib

# Results

Among all tested models, Random Forest achieved the best predictive performance.

The project also includes:

- Feature Importance Analysis
- Residual Analysis
- Actual vs Predicted Visualization
- Cross Validation
- Hyperparameter Tuning


