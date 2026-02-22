# Lab 3 – Exploratory Data Analysis (EDA)

## 📌 Overview
This lab focuses on performing Exploratory Data Analysis (EDA) on a medical insurance dataset.  
The goal is to understand the dataset structure, detect patterns, identify relationships, and extract meaningful insights before building predictive models.

---

## 📊 Dataset Information
- **Dataset Name:** Medical Cost Personal Dataset  
- **Source:** Kaggle  
- **Number of Records:** 1,337 (after removing duplicates)  
- **Number of Features:** 7  

### Features:
- age  
- sex  
- bmi  
- children  
- smoker  
- region  
- charges  

---

## 🔍
Analysis Performed

### 1️⃣ Data Overview
- Checked dataset shape
- Inspected data types
- Verified missing values
- Removed duplicate records

### 2️⃣ Univariate Analysis
- Age distribution
- BMI distribution
- Charges distribution
- Categorical variable distributions (smoker, region)

### 3️⃣ Bivariate Analysis
- Smoker vs Charges (strongest relationship)
- Age vs Charges
- Correlation Matrix

---

## 🔥 Key Findings
- Medical charges are highly right-skewed.
- Smoking status is the strongest factor influencing insurance costs.
- Age and BMI show positive relationships with medical charges.
- The dataset is clean and suitable for predictive modeling.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
