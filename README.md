# 📊 Customer Churn Analysis — Exploratory Data Analysis (EDA) & Hypothesis Testing

![Churn Analysis Banner](banner.png)

## 🧠 Project Overview

This project was developed as part of the final assignment for the **IBM Machine Learning with Python** Coursera specialization. It is a comprehensive demonstration of how to:

* Explore a real-world dataset
* Perform advanced EDA
* Formulate hypotheses
* Conduct hypothesis testing
* Derive actionable insights for business decision-making

Our analysis focuses on understanding **customer churn behavior** using statistical and visual techniques, paving the way for churn prediction models in future phases.

---

## 🧾 IBM Project Brief

**Objective:** Apply analytical and data science skills to explore a dataset, conduct hypothesis testing, and prepare it for machine learning.

You must:

* Analyze and summarize a dataset
* Clean and visualize it
* Identify key patterns and formulate hypotheses
* Perform at least one hypothesis test
* Report the findings in a professional and insightful manner

Your submission is graded on:

* Dataset summary
* EDA quality
* Data cleaning/feature engineering
* Key findings
* Hypothesis formulation and significance testing

---

## 📦 Dataset Details

* **Name:** `customer_churn_dataset-testing-master.csv`
* **Source:** Provided in the IBM ML course
* **Type:** Tabular data (CSV format)
* **Rows:** \~45,000
* **Columns:**

  * Customer ID, Gender, Age, Tenure, Subscription Type, Contract Length
  * Support Calls, Payment Delay, Usage Frequency, Total Spend, Churn

---

## 🔍 Analysis Highlights

### 📑 1. Dataset Summary

* Overview of column types, missing values, and unique counts
* Target variable: `Churn`

### 🧭 2. Data Exploration Plan

* Focused on spending behavior, customer engagement, and churn status
* Analyzed how churn varies across subscription types, contracts, and usage patterns

### 📊 3. Exploratory Data Analysis (EDA)

* Correlation heatmap between numerical features
* Violin plots & KDEs for distribution analysis
* Grouped bar plots by `Contract` and `Subscription Type`

### 🧹 4. Data Cleaning & Feature Engineering

* Handled missing values and invalid entries
* Encoded categorical variables
* Created new features like `Avg Spend per Month`

### 💡 5. Key Findings

* Total Spend and Tenure are highly correlated
* Customers with longer contracts tend to churn less
* Churn rates don’t significantly vary across Subscription types (confirmed via Chi-Square test)

### 🧪 6. Hypotheses Tested

1. **ANOVA:** Does Contract Length affect Total Spend?

   * ✅ Significant (p < 0.001)
2. **T-Test:** Do churned customers make more support calls?

   * ❌ Not significant (p = 0.158)
3. **Chi-Square:** Does Subscription Type affect Churn?

   * ❌ Not significant (p = 0.829)

### ✅ 7. Conclusion

* Statistically validated findings support that **contract length impacts spend and churn**.
* Support calls and subscription types have **no strong association** with churn.

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy, SciPy, Seaborn, Matplotlib)
* Google Colab
* Jupyter Notebook

---

## 🖼️ Visual Gallery

All plots saved in the `images/` folder. Includes:

* 📈 Heatmap of Correlation
* 🪄 KDE & Violin Plots by Contract
* 📊 Bar plots of grouped means
* 🧱 Chi-square stacked bars

---

## 💾 Run This Project

```bash
# Clone the repo
$ git clone https://github.com/yourusername/customer-churn-eda-ml.git

# Open the notebook in Colab
https://colab.research.google.com/github/yourusername/customer-churn-eda-ml/blob/main/Final_Project_EDA.ipynb
```

---

## 📌 Future Work

* Feature selection & model training (Logistic Regression, XGBoost)
* SHAP explainability and churn probability dashboard (Gradio/Streamlit)

---

## 👨‍💻 Author

**Tamaghna Nag**

* ML Engineer | AI Innovator | NovalQ Founder
* 🔗 [Portfolio](https://tamaghnatech.in) | [GitHub](https://github.com/Tamaghnatech) | [LinkedIn](https://www.linkedin.com/in/tamaghna99/)

---

## 📜 License

MIT License
