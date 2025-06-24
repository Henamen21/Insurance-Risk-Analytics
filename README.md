# 🚗 Insurance Risk Analytics — Optimizing Premiums with Data and Curiosity

## 📌 Project Overview

AlphaCare Insurance Solutions (ACIS) aims to optimize premiums and identify low-risk customer segments using historical insurance claim data. This project explores that objective through exploratory data analysis, hypothesis testing, machine learning, and data versioning.

---

## 🧠 Business Problem

- Identify **low-risk clients** eligible for **lower premiums**
- Improve **marketing strategies** through better risk segmentation
- Build a model to predict **claim severity** and optimize pricing

---

## 📂 Task Breakdown

### 🔹 Task 1: Exploratory Data Analysis (EDA)
- Loaded raw `.txt` data using Pandas
- Handled formatting issues (e.g., European-style commas in floats)
- Explored distributions of:
  - `TotalPremium`
  - `TotalClaims`
  - `SumInsured`, etc.
- Detected outliers and visualized trends using Seaborn & Matplotlib

### 🔹 Task 2: Data Version Control (DVC)
- Initialized DVC and tracked `cleaned_df.csv`
- Configured local remote storage
- Ensured reproducibility of data pipeline with versioned data

### 🔹 Task 3: A/B Hypothesis Testing
- Conducted:
  - ANOVA (e.g., Province vs. Claims)
  - Z-tests (e.g., Gender vs. Claim probability)
  - T-tests (e.g., PostalCode vs. Margin)
- Interpreted p-values to statistically validate risk differences

### 🔹 Task 4: Predictive Modeling
- Built models for **claim severity** prediction:
  - Linear Regression
  - Random Forest
  - XGBoost
- Used **SHAP** for model interpretability
- Identified top features influencing claim amounts

---

## 📊 Insights and Recommendations

### 🔍 Data Insights
- Certain provinces and zip codes consistently showed **higher claims**
- **Gender and vehicle type** had statistically significant risk differences
- **XGBoost** outperformed other models in predicting claim severity

### 💡 Business Recommendations
- Offer **discounts to low-risk segments** (e.g., married, certain postal codes)
- **Refine marketing** using top predictive features like:
  - Vehicle type
  - Cylinders
  - Tracking device presence
- Use DVC and Git to maintain reproducible workflows

---

## 📎 Project Assets

- 🔗 GitHub Repository: [Insurance-Risk-Analytics](https://github.com/Henamen21/Insurance-Risk-Analytics)
- 📓 Notebooks: EDA, Hypothesis Testing, Modeling
- 🛠️ Scripts: `scripts/utils.py`, `scripts/stat_tests.py`
- 📁 Data tracked and versioned using DVC

---

## ✅ Conclusion

This project combined curiosity-driven analysis, rigorous statistics, and machine learning to produce actionable strategies for ACIS. With a reproducible pipeline and model interpretability in place, ACIS is positioned to refine its premium structure and scale smartly.

---

*Submitted as part of 10 Academy KAIM Week 3 Challenge.*
