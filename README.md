# 🚀 Customer Churn Intelligence & Profit Optimization System

> Transforming churn prediction into a revenue-driven decision strategy.

---

## 📌 Executive Summary

A telecom company with a **26.54% churn rate** was losing approximately **3.68M in revenue**.

Instead of building a standard churn classifier, this project delivers:

- 🔮 Predictive churn modeling  
- 🧠 Explainable AI insights  
- 💰 Profit-based customer prioritization  
- 🌐 Deployment-ready decision support tool  

This solution bridges **Data Science, Business Strategy, and Product Deployment**.

---

## 📊 Business Context

- 👥 7,043 Customers  
- 💰 21.37M Total Revenue  
- 📉 26.54% Churn Rate  
- 💸 3.68M Revenue Lost  
- 📈 Avg CLTV: 4.4K  

The key business question:

> Who is likely to churn — and who is expensive to lose?

---

## 🔎 Analytical Approach (Consulting Lens)

### 1️⃣ Exploratory Data Analysis

Identified structural churn patterns:

- Month-to-Month contracts show highest churn
- Early tenure (0–6 months) customers are high-risk
- High monthly charges increase churn probability
- Competitor offers strongly influence churn behavior
- Refund behavior signals dissatisfaction

Churn was not random — it followed behavioral and lifecycle patterns.

---

### 2️⃣ Feature Engineering Strategy

To move beyond basic modeling:

- Tenure Bucketing (Lifecycle Stages)
- CLTV Segmentation (Low / Medium / High)
- Revenue per Month Ratio
- Revenue Deviation (Behavioral instability signal)
- Customer Value Segments

Business-driven features, not just statistical ones.

---

### 3️⃣ Handling Class Imbalance

Churn problems are inherently imbalanced.

Applied:
- Class Weight balancing
- Performance comparison before/after

Optimized for Recall & AUC instead of Accuracy.

Because:

> Missing a churner costs revenue.

---

### 4️⃣ Predictive Modeling

Model: Logistic Regression (interpretable baseline)

Why?
- Business interpretability
- Stable decision boundary
- Suitable for structured telecom data

Evaluation Metrics:
- Recall (Churn class)
- ROC-AUC
- Confusion Matrix

---

### 5️⃣ Model Explainability

Implemented:
- Feature Importance
- SHAP Values

Top churn drivers:

1. Short-term contracts  
2. Low tenure  
3. High monthly charges  
4. Lack of premium support  
5. Competitor dissatisfaction  

The model explains *why*, not just *what*.

---

## 💰 Profit-Based Prioritization Layer

Traditional churn models output probability.

This project introduces:

> **Priority Score = Churn Probability × CLTV**

This allows the business to:

- Target high-risk, high-value customers first
- Allocate retention budget efficiently
- Maximize ROI of retention campaigns

Prediction → Decision → Profit Impact.

---

## 🌐 Deployment

Built an interactive application using **Streamlit** featuring:

- Real-time churn prediction
- Customer-level explanation
- Risk categorization
- Priority ranking dashboard

🔗 Live Demo:  
[Insert Streamlit Link Here]

---

## 🛠 Technical Stack

- Python  
- Pandas / NumPy  
- Scikit-learn  
- SHAP  
- Streamlit  
- Power BI  

---

## 📈 What This Project Demonstrates

### From a Recruiter Perspective:

✔ End-to-end ML pipeline  
✔ Feature engineering expertise  
✔ Imbalance handling  
✔ Explainable AI  
✔ Model deployment  

### From a Consulting Perspective:

✔ Business-first thinking  
✔ Revenue-driven prioritization  
✔ Lifecycle-based segmentation  
✔ Profit optimization logic  
✔ Decision-support system design  

---

## 📬 About Me

**Mohamed Eid Shehata**  
Data Analyst | Data Scientist  
Giza, Egypt  

Passionate about turning data into business strategy and deployable intelligence systems.
