# 📊 Customer Churn & Retention Analytics

An end-to-end Data Analytics project that cleans, structures, and analyzes multi-table customer subscription data to identify churn drivers, quantify revenue at risk, and deliver actionable retention strategies.

---

## 📌 Project Overview
Customer churn is one of the most critical metrics for subscription-based business models. This project performs exploratory data analysis (EDA) across customer demographics, subscription plans, and support tickets to understand **why customers leave** and **how to retain them**.

---

## 🔑 Key Metrics & Insights
* **Total Customer Base:** 21
* **Overall Churn Rate:** 28.57% (6 Cancellations)
* **Retention Rate:** 71.43%
* **Average Revenue Per User (ARPU):** ₹18.85
* **Monthly Revenue at Risk:** ₹73.94

---

## 📈 Major Findings
1. **High Churn in Basic Plan:** ~60% churn rate observed among Basic Plan subscribers, indicating potential value gap or feature limitations.
2. **Top Churn Drivers:**
   * Switched to competitors
   * High pricing / Service cost
   * Streaming / Content quality issues
3. **Customer Support Impact:** Customers with low CSAT scores and escalated support tickets showed a significantly higher churn probability.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Database & File Format:** SQL / Multi-Sheet Excel (`db_customer`, `db_subscription`, `db_support`)

---

## 📁 Repository Structure
```text
Customer-Churn-Analysis/
│
├── data/
│   └── customer_churn_data_raw.xlsx
│
├── visualizations/
│   └── churn_analysis_summary.png
│
├── README.md
└── churn_analysis.py
