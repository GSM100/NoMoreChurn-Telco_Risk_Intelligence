📉 NoMoreChurn – Telco Risk Intelligence

**Predict. Prevent. Retain.**

A full-stack churn prediction and risk intelligence system powered by machine learning and Power BI.

---

## 🚀 Project Overview

**NoMoreChurn – Telco Risk Intelligence** is a comprehensive churn prediction and analysis project for the telecom industry. This solution combines machine learning modeling with interactive data visualizations to identify at-risk customers, understand churn behavior, and help businesses take preventive action.

---

## 🧠 Core Objectives

- Predict telecom customer churn using ML algorithms.
- Identify the most important features driving churn.
- Build intuitive Power BI dashboards to present churn insights.
- Enable business stakeholders to explore risk and take decisions based on customer-level analysis.
- Automate churn risk scoring and persona profiling.

---

## 📂 Project Structure

```
NoMoreChurn-Telco-Risk-Intelligence/
├── Data/
│   └── telecom churn Rate Raw Dataset.xlsx
├── Notebooks/
│   └── churn_model.ipynb
├── Model_Dataset/
│   └── Final Churn Data after Modeling.csv
├── PowerBI/
│   └── churn Visualization.pbix
```

---

## ⚙️ Tools & Technologies

| Layer         | Tools / Libraries                                                |
|---------------|------------------------------------------------------------------|
| Programming   | Python (pandas, numpy, matplotlib, seaborn)                      |
| Modeling      | scikit-learn, XGBoost, GridSearchCV, VotingClassifier            |
| IDE           | Jupyter Notebook                                                 |
| Dashboarding  | Power BI Desktop                                                 |
| ML Techniques | K-Fold CV, Feature Engineering, Soft Voting, AUC-ROC             |
| Deployment    | Power BI Interactive Dashboard                                   |

---

## 🧪 Machine Learning Pipeline

- **Data Cleaning & EDA**
- **Feature Engineering** (Encoding, Binning, Scaling)
- **Train-Test Split (80/20)**

**Models Used:**
- Random Forest (with K-Fold & GridSearchCV)
- XGBoost
- Voting Classifier (Soft Voting)

**Evaluation Metrics:**
- Accuracy
- Precision
- Recall
- Confusion Matrix
- AUC-ROC

**Final Output:** Churn Prediction + Probability Score for each customer

---

## 📈 Power BI Dashboard Overview

### 🧾 Sheet 1: Churn Overview & Model Performance
- **KPI Cards**:
  - Total Customers (Test)
  - Churned Customers (Actual)
  - Predicted Churned Customers
  - Model Accuracy
- **Charts**:
  - Actual vs Predicted Churn (Clustered bar)
  - Confusion Matrix (TP, FP, TN, FN)
  - Precision & Recall Cards
  - Gauge/Pie: Actual vs Predicted Churn Rates

### 🧾 Sheet 2: Churn Analysis by Customer Attributes
- Churn Rate by:
  - Contract Type
  - Payment Method
  - Tenure Bins (0–12, 13–24…)
- Scatter Plot:
  - MonthlyCharges vs TotalCharges (color = churn)
- Churn Rate by:
  - Gender (Pie)
  - Partner & Dependents (100% bar)
- **Churn Persona Card**:
  - Filters by customer → shows tenure, charges, churn probability

### 🧾 Sheet 3: Churn Risk & Ticket Impact
- Table: Top 10 High-Risk Customers (churn prob., tenure, charges)
- Histogram: Churn Probability Bands
- Feature Histograms: Risk by key attributes

---

## 📊 Key Evaluation Metrics

- **Model Accuracy**: >85%
- **AUC-ROC Curve** Analysis
- **Precision & Recall**: >75%
- **Confusion Matrix Breakdown**
- **Prediction Band Distribution**

---

## 🧪 Sample Output

| customerID   | Actual Churn | Predicted Churn | Churn Probability |
|--------------|---------------|------------------|--------------------|
| 5582-TYFJP   | Yes           | Yes              | 0.91               |
| 6278-NUJAA   | No            | No               | 0.12               |
| 8792-AFYUV   | Yes           | No               | 0.47               |

---
👤 Author & Contact

Name: Gourisankar Maity
Email: maitygourisankar0@gmail.com
LinkedIn: https://www.linkedin.com/in/gourisankar-maity-73a5492aa
