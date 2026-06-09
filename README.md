# 🏥 Medical Insurance Data Analysis and Preprocessing

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) and data preprocessing on a medical insurance dataset using Python. The objective is to analyze the factors that influence medical insurance charges and prepare the dataset for future machine learning models.

The project demonstrates a complete data preprocessing workflow, including data cleaning, visualization, feature engineering, feature scaling, and feature selection.

---

## 🎯 Objectives

- Analyze the medical insurance dataset.
- Understand the relationship between different features and insurance charges.
- Perform data cleaning and preprocessing.
- Encode categorical variables.
- Create new features for improved analysis.
- Standardize numerical features using feature scaling.
- Identify the most important features using statistical methods.

---

## 📂 Dataset

**Dataset:** Medical Cost Personal Dataset

**Source:**
https://www.kaggle.com/datasets/mirichoi0218/insurance

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading
- Imported the insurance dataset using Pandas.
- Explored the dataset structure and data types.

### 2. Exploratory Data Analysis (EDA)
- Checked dataset shape and summary statistics.
- Identified missing values and duplicate records.
- Visualized feature distributions.
- Analyzed relationships between variables.

### 3. Data Cleaning
- Removed duplicate records.
- Verified missing values.
- Corrected data types where required.

### 4. Feature Engineering
- Created a new **BMI Category** feature.
- Encoded categorical variables such as:
  - Gender
  - Smoker
  - Region

### 5. Feature Scaling
Applied **StandardScaler** on:
- Age
- BMI
- Children

### 6. Feature Selection
Performed:
- Pearson Correlation Analysis
- Chi-Square Test

to identify the most influential features affecting insurance charges.

---

## 📈 Key Findings

- Smoking status has the strongest positive relationship with insurance charges.
- Age significantly impacts medical insurance costs.
- BMI contributes to increased insurance expenses.
- Feature scaling prepares numerical data for machine learning algorithms.
- Statistical feature selection helps identify the most relevant features.

---

## 📁 Repository Structure

```
Medical-insurance-eda/
│
├── insurance_analysis.ipynb
├── insurance.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- Train Machine Learning Models
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Evaluate models using:
  - MAE
  - RMSE
  - R² Score
- Hyperparameter tuning
- Deploy the project using Streamlit

---

## 👩‍💻 Author

**Nandini Rao**

Aspiring AI & Machine Learning Engineer

**GitHub Profile:**
https://github.com/nandinirao6900-dotcom

**Project Repository:**
https://github.com/nandinirao6900-dotcom/Medical-insurance-eda-

---

## ⭐ Support

If you found this project useful or learned something from it, consider giving the repository a ⭐.
