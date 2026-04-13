# 💼 Tata x Forage – GenAI Powered Data Analytics (Delinquency Risk & Collections Strategy)

This repository contains my work for the **Tata iQ × Forage GenAI Powered Data Analytics Simulation**, where I worked as an **AI Transformation Consultant** on a credit risk analytics project for Geldium Finance.

The objective was to design an **AI-driven system to predict credit card delinquency and improve collections strategy** using data analytics, machine learning, and responsible AI principles.

---

## 🔎 Business Problem

Geldium Finance observed an increasing delinquency rate (~16%) and required a more efficient, data-driven approach to:

- Identify high-risk customers before missed payments  
- Prioritize collections outreach  
- Design targeted intervention strategies  
- Ensure fairness, transparency, and explainability in AI-driven decisions  

---

## 📊 Dataset Overview

- **500 customers | 19 variables**  
- Target: `Delinquent_Account (0/1)`  
- Class imbalance: **84% non-delinquent / 16% delinquent**

Data included:
- Customer demographics (age, income, location)  
- Financial attributes (credit score, utilization, DTI)  
- Behavioral data (missed payments, 6-month payment history)

---

## 🧠 Task 1 — Exploratory Data Analysis

Conducted a full EDA to understand data quality, patterns, and risk signals.

### Key Findings:
- High Debt-to-Income ratio (>40%) strongly correlates with delinquency  
- Unemployed customers show the highest delinquency rates  
- Payment history trends are the strongest behavioral predictors  
- Credit score showed non-linear relationship with delinquency  

### Data Preparation:
- Median imputation for missing values (Income, Credit Score, Loan Balance)  
- Standardization of inconsistent categorical values  
- Correction of anomalies (e.g., credit utilization > 1.0)

---

## 🤖 Task 2 — Predictive Model Design

Designed a machine learning pipeline to predict delinquency risk.

### Model:
- **XGBoost Classifier (Gradient Boosted Trees)**

### Key Features:
- Debt-to-Income Ratio  
- Employment Status  
- Missed Payments  
- Payment History (Month 1–6)  
- Credit Utilization  

### Pipeline:
- Data cleaning and preprocessing  
- Feature engineering (Payment Risk Score)  
- Handling class imbalance using SMOTE  
- Model training and probability-based predictions  
- Explainability using SHAP values  

---

## 📈 Task 3 — Business Strategy & Recommendations

Translated model insights into actionable business strategies.

### Top Risk Drivers:
- High DTI (>40%)  
- Unemployment  
- Deteriorating payment history  

### Strategy:
- Target high-risk segments (e.g., unemployed + high DTI)  
- Early intervention through SMS and outreach  
- Offer support-based solutions (hardship plans)

### Expected Impact:
- ~15–20% reduction in delinquency  
- Improved collections efficiency  
- Better customer engagement  

---

## ⚙️ Task 4 — AI-Powered Collections System

Designed an end-to-end AI-driven decision system:

### Workflow:
1. Input customer data  
2. Model predicts delinquency probability  
3. Customers categorized into risk tiers  
4. Actions triggered:
   - Low risk → automated reminders  
   - Medium → SMS nudges  
   - High → manual intervention  
5. Continuous learning via retraining and monitoring  

---

## 🛡️ Responsible AI Approach

- SHAP-based explainability for each prediction  
- Fairness checks across demographic groups  
- Human-in-the-loop decision making  
- Regular model monitoring and retraining  
- Avoidance of proxy bias (e.g., age, location)

---

## 🚀 Key Outcomes

- 15–20% potential reduction in delinquency  
- 30% reduction in manual effort  
- Improved risk identification accuracy  
- Scalable AI-driven decision system  

---

## 📄 Project Deliverables

- Exploratory Data Analysis Report  
- Predictive Model Plan  
- Business Summary Report  
- AI Strategy Presentation  
- Certificate  

---

## 🎓 Certificate

🔗 **View Certificate:**  
[GenAI Data Analytics Certificate](https://github.com/KavyaSingh236/GenAI_Powered_Data_Analytics/blob/main/tata_genai_data_analytics.pdf)

---

## 🤖 GenAI Usage

GenAI was used to:
- Assist in structuring analysis and modeling approach  
- Summarize insights and identify patterns  
- Improve clarity of business recommendations  

All outputs were validated using analytical reasoning and domain understanding.

---

## 👤 Author

**Kavya Balaji Singh**  
