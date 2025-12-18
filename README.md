# 📉 Customer Churn Analysis & Retention Strategy

## 📌 Project Overview
Customer churn is a critical problem for subscription-based businesses such as telecom and SaaS companies.  
This project focuses on analyzing customer behavior to **identify churn patterns**, **understand key churn drivers**, and **provide actionable retention strategies** using data analytics and light machine learning.

The project is designed at an **intermediate Data Analyst level**, emphasizing exploratory analysis, business insights, and practical decision-making.

---

## 🎯 Objectives
- Understand overall churn behavior
- Identify key factors influencing customer churn
- Analyze churn across contracts, tenure, services, and charges
- Segment customers into risk categories
- Build a baseline predictive model for churn detection
- Provide actionable business recommendations

---

## 🗂 Dataset Information
- **Source:** Kaggle – Customer Churn Dataset  
- **Files Used:**
  - `customer_churn_dataset-training.xlsx`
  - `customer_churn_dataset-testing.xlsx`
- Both files share the same structure and were combined for comprehensive analysis.

### Key Features:
- `tenure`
- `MonthlyCharges`
- `TotalCharges`
- `Contract`
- `PaymentMethod`
- `InternetService`
- `SeniorCitizen`
- `Churn` (Target Variable)

---

## 🛠 Tools & Technologies
- **Programming Language:** Python  
- **Libraries Used:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Environment:** Jupyter Notebook / Kaggle Notebook  

---

## 📊 Project Workflow

### 1️⃣ Data Preparation
- Combined training and testing datasets
- Handled missing values and data type issues
- Converted categorical variables into numerical format
- Removed irrelevant identifiers

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Churn distribution analysis
- Churn vs Contract Type
- Churn vs Tenure
- Churn vs Monthly Charges
- Service-wise churn comparison

Visualizations were used extensively to highlight churn trends and patterns.

---

### 3️⃣ Feature Engineering
- Created tenure groups to segment customer lifecycle stages
- Encoded categorical variables for modeling
- Prepared features for predictive analysis

---

### 4️⃣ Predictive Modeling (Baseline)
- Built a **Logistic Regression** model
- Evaluated performance using:
  - Confusion Matrix
  - Precision, Recall, and F1-Score

This model serves as a baseline to understand churn predictability.

---

## 🔍 Key Insights
- Customers on **month-to-month contracts** have significantly higher churn
- **New customers** are more likely to churn than long-tenured users
- Higher **monthly charges** increase churn probability
- Customers using **fiber optic internet services** show higher churn rates

---

## 💡 Business Recommendations
- Encourage long-term contracts with incentives
- Provide targeted discounts for high-charge customers
- Improve onboarding experience for new customers
- Run retention campaigns for high-risk customer segments

---

## 📁 Project Structure
Customer-Churn-Analysis/
│
├── Customer_Churn.ipynb
├── customer_churn_dataset-training.xlsx
├── customer_churn_dataset-testing.xlsx
└── README.md
---

## 🚀 Future Enhancements
- Advanced models (Random Forest, XGBoost)
- Feature importance analysis
- Customer segmentation using clustering
- Interactive dashboards (Power BI / Tableau)

---

## 👤 Author
**Niranjan NN**  
Aspiring Data Analyst | Kaggle Contributor  
- GitHub: https://github.com/Niranjan-NN  
- Kaggle: https://www.kaggle.com/  

---
