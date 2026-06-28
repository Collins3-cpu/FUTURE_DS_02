# FUTURE_DS_02
Future Interns Data Science & Analytics Task 2 Repository
# Customer Retention & Churn Analysis

**Telco Customer Churn Prediction & Retention Strategy**

![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange) ![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![Pandas](https://img.shields.io/badge/Pandas-2.x-green)

## 📋 Project Overview

This project analyzes customer churn for a **telecom subscription service** using the famous Telco Customer Churn dataset. The goal is to understand **why customers leave**, identify high-risk segments, and provide **actionable recommendations** to improve retention and increase Customer Lifetime Value (CLV).

### DataSource
I downloaded the original dataset from Kaggle: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

### Key Business Questions Answered:
- Why are customers leaving?
- Which customer segments are most likely to churn?
- How long do customers typically stay?
- What actions can significantly improve retention?

---

## 📁 Repository Contents

- `Task2.ipynb` → Main Jupyter Notebook (full analysis)
- `Customer_data.csv` → Original dataset (7043 records)
- `/Task2Screenshot/` → Folder containing all visualization screenshots
- `README.md` → This file

---

## 🛠️ Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-learn** (Random Forest Classifier)
- **Jupyter Notebook**

---

## 📊 Key Insights

### Churn Rate
- **Overall Churn Rate**: **26.54%** (1,869 churned customers)

### Major Findings
- **Contract Type** is the strongest predictor:
  - Month-to-month → **42.8%** churn
  - Two-year contracts → **2.8%** churn
- Customers churn heavily in the **first 12 months** (especially first 6 months)
- Electronic check payers and Fiber optic users show higher churn
- **Online Security** and **Tech Support** significantly reduce churn
- Retained customers have ~**$1,018 higher CLV** on average

### Model Performance
- Random Forest model achieved **80.6% accuracy**
- Top predictors: Tenure, Total Charges, Monthly Charges, Contract Type

---

## 🎯 Business Recommendations

1. **Launch contract upgrade campaigns** for month-to-month customers (highest impact)
2. Strengthen **onboarding & engagement** in the first 6–12 months
3. Promote **service bundles** (Online Security + Tech Support)
4. Incentivize customers to switch to **automatic payments**
5. Use the predictive model for **proactive retention** targeting

---

## 📈 Visualizations Included

- Churn rate by Contract, Payment Method, and Internet Service
- Tenure distribution and retention curve
- Monthly charges & CLV comparison
- Feature importance from ML model
- Correlation heatmap
- Cohort analysis

*(All charts available in the `/Task2Screenshot/` folder)*

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone <https://github.com/Collins3-cpu/FUTURE_DS_02>
   cd customer-churn-analysis

