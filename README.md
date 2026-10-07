# 📊 Customer Churn Prediction & Retention Strategy Engine

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Project Overview
End-to-end predictive classification model built with **Python** and **Random Forest** to analyze over 500,000 customer records. This project identifies critical drivers behind customer churn and provides actionable business recommendations to improve customer retention.

---

## 💡 Business Problem
High customer attrition directly impacts recurring revenue. The business objective is to:
1. Predict high-risk churn customers before they discontinue their service.
2. Identify the primary behavioral indicators driving churn.
3. Formulate targeted intervention strategies for the customer success team.

---

## 🔑 Key Findings & Business Insights
* **Support Calls**: The primary indicator of churn. Customers making 4+ support calls exhibit a significantly higher tendency to churn due to unresolved technical bottlenecks.
* **Payment Delay**: Late bill payments (>10 days) strongly correlate with decreasing commitment and satisfaction.
* **Total Spend & Engagement**: Low-spending accounts with long gaps since their last interaction represent the highest churn risk group.

---

## 🛠️ Tech Stack & Workflow
* **Language & Environment**: Python, Jupyter Notebook / VS Code
* **Data Manipulation**: Pandas, NumPy
* **Data Visualization**: Matplotlib, Seaborn
* **Machine Learning**: Scikit-Learn (Random Forest Classifier, Logistic Regression)

### Workflow Steps:
1. **Data Cleaning**: Handled missing values and dropped non-predictive identifiers (`CustomerID`).
2. **Exploratory Data Analysis (EDA)**: Analyzed feature distributions and behavioral patterns across churned vs. retained users.
3. **Feature Engineering & Encoding**: Applied One-Hot Encoding for categorical variables (`Gender`, `Subscription Type`, `Contract Length`).
4. **Model Training & Evaluation**: Trained baseline and ensemble models, evaluated via ROC-AUC and Feature Importance.

---

## 📈 Model Performance
* **Selected Model**: Random Forest Classifier
* **Primary Drivers Evaluated**: `Support Calls`, `Total Spend`, `Age`, `Contract Length (Monthly)`, `Payment Delay`

---

## 🚀 How to Run Locally
```bash
# Clone repository
git clone [https://github.com/username-anda/customer-churn-prediction.git](https://github.com/username-anda/customer-churn-prediction.git)

# Navigate into project directory
cd customer-churn-prediction

# Open project in VS Code or Jupyter Notebook
code .