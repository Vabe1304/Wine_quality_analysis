# 🍷 Wine Quality Data Cleaning and Imputation

This project focuses on **data loading, exploratory data analysis (EDA), data cleaning, and missing value imputation** using the **Red Wine Quality dataset** from the UCI Machine Learning Repository.

The main goal is to demonstrate **good data preprocessing practices** before applying Machine Learning models.

---

## 📌 Dataset

- **Name:** Wine Quality – Red Wine  
- **Source:** UCI Machine Learning Repository  
- **Observations:** 1,599 samples  
- **Features:** 11 physicochemical variables + 1 target variable (`quality`)

---

## 🧰 Tools & Libraries

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- SciPy  

---

## 🔍 Project Overview

### 1. Data Loading
- Dataset loaded directly from the UCI repository
- Basic inspection of shape, data types, and sample rows

### 2. Exploratory Data Analysis (EDA)
- Descriptive statistics
- Distribution of wine quality
- Alcohol content distribution
- Correlation analysis

### 3. Data Cleaning (Key Steps)
- Handling missing values
- Standardizing column names
- Date format unification
- Outlier detection (IQR and z-score)
- Removing duplicates
- Numeric and text normalization
- Feature categorization

### 4. Missing Data Imputation
Artificial missing values (15%) were generated and handled using:
- Mean imputation
- Median imputation
- Mode imputation
- KNN imputation

The methods were compared, and **mean imputation** was selected for the final dataset.

---

## 🎯 Purpose

- Practice real-world data cleaning techniques
- Understand different imputation strategies
- Prepare data for Machine Learning models
- Build a solid Data Science portfolio project

---

## 👩‍💻 Author

**Valentina Agudelo Echeverri**  
Biological Engineer  
National University of Colombia

---

## 📜 License

This project uses publicly available data from the UCI repository and is intended for educational purposes.
