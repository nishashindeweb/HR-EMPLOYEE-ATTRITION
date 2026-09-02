

# HR Employee Attrition Analysis & Prediction

This project analyzes HR data to understand why employees leave and predicts attrition using Machine Learning to help HR retain talent.

## 📌 Problem Statement
Employee attrition is a major cost for companies. The goal is to identify key factors driving attrition and build a model to predict employees at risk of leaving.

## 📊 Dataset
- **Source:** IBM HR Analytics Employee Attrition Dataset (Kaggle)
- **Rows:** 1470 employees
- **Columns:** 35 features (Age, Department, JobSatisfaction, MonthlyIncome, OverTime, etc.)
- **Target:** Attrition (Yes/No)

## 🔍 What I Did

### 1. Exploratory Data Analysis (EDA)
- Checked attrition rate (~16% left)
- Analyzed attrition by Department, JobRole, OverTime, JobSatisfaction, Age, Income
- Found key insights: Employees with OverTime, Low Job Satisfaction, and Low Income leave more.

### 2. Data Preprocessing
- Handled categorical variables with One-Hot Encoding
- Scaled numerical features
- Handled class imbalance with SMOTE

### 3. Models Used
- Logistic Regression
- Random Forest
- XGBoost

### 4. Results
| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- | :--- |
| Logistic Regression | 85% | 0.82 | 0.78 | 0.80 |
| Random Forest | 88% | 0.86 | 0.84 | 0.85 |
| XGBoost | 89% | 0.88 | 0.86 | 0.87 |

> Best Model: **XGBoost with 89% Accuracy**

## 🛠️ Tech Stack
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-Learn, XGBoost, Imbalanced-learn
- Jupyter Notebook
