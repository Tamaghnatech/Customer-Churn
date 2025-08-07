<h1 align="center">📊 Customer Churn Analysis – EDA & Hypothesis Testing</h1>

<p align="center">
  <img src="banner.png" alt="Customer Churn Banner" width="80%">
</p>

<p align="center"><em>IBM Advanced Data Science Capstone Project | Hypothesis Testing & Insights</em></p>

> 💡 Goal: Extract actionable insights, validate business hypotheses, and evaluate customer behavior patterns using rigorous data science techniques.

---

## 🧠 Project Origin – IBM Capstone Summary

This project was assigned as the **final practice module** in the IBM Advanced Data Science Specialization. The aim was to:
- Demonstrate EDA and hypothesis testing skills.
- Work with real-world business datasets.
- Communicate data-driven findings effectively.

The submission was **auto-graded using AI Mark**, and evaluation was based on completeness, insightfulness, statistical validity, and presentation.

---

## 📁 Dataset Summary

- **File:** `customer_churn_dataset-testing-master.csv`
- **Source:** Provided as part of the IBM Capstone Course
- **Size:** ~50,000 records
- **Key Fields:**
  - `Churn` (0 = No churn, 1 = Churn)
  - `Subscription Type`, `Contract`, `Tenure`, `Total Spend`, `Support Calls`, etc.

---

## 🔍 Project Workflow

| Step | Task |
|------|------|
| ✅ 1. **Dataset Summary** | Overview of variables, nulls, and distributions |
| ✅ 2. **Exploration Plan** | Vision for what insights to explore and why |
| ✅ 3. **EDA** | Univariate, bivariate, and multivariate analyses |
| ✅ 4. **Data Cleaning & Feature Engineering** | Null handling, type correction |
| ✅ 5. **Key Findings** | Synthesized insights from all analysis |
| ✅ 6. **Hypothesis Formulation** | Defined 3 hypotheses from business logic |
| ✅ 7. **Hypothesis Testing** | ANOVA, T-test, Chi-square, p-values |
| ✅ 8. **Conclusion & Next Steps** | Actionable recommendations |

---

## 📌 Key Insights

- 🔹 **Tenure** and **Total Spend** are strongly positively correlated.
- 🔹 Customers with **longer contracts** tend to spend more.
- 🔹 No statistically significant difference in support calls across churn outcomes.
- 🔹 **Subscription Type** is not associated with churn (Chi-Square test).
- 🔹 **Contract Length** does significantly affect spending (ANOVA test).

---

## 🧪 Hypothesis Testing Results

| Hypothesis | Test | P-Value | Result |
|------------|------|---------|--------|
| Spend differs by Contract Type | ANOVA | 0.0000 | ✅ Significant |
| Support Calls affect Churn | T-Test | 0.1589 | ❌ Not Significant |
| Churn depends on Subscription Type | Chi-Square | 0.8294 | ❌ Not Significant |

---

## 🖼️ Screenshot Gallery

| Plot | Description |
|------|-------------|
| ![](./download%20(96).png) |
| ![](./download%20(97).png) | 
| ![](./download%20(98).png) | 
| ![](./download%20(99).png) | 
| ![](./download%20(100).png) | 
| ![](./download%20-%202025-08-07T065411.508.png) | 
| ![](./download%20-%202025-08-07T070106.741.png) | 
| ![](./download%20-%202025-08-07T070435.722.png) | 
| ![](./download%20-%202025-08-07T070935.995.png) | 

> 💡 All plots were generated using `seaborn`, `matplotlib`, and `pandas` in Google Colab.

---

## ⚙️ Tools & Libraries Used

- **Python 3.11**
- **Google Colab**
- **pandas, seaborn, matplotlib**
- **scipy.stats, statsmodels**
- **plotly (optional)**

---

## 🔧 Setup Instructions

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels
````

Run the notebook on [Google Colab](https://colab.research.google.com/) and upload the dataset to `/content`.

---

## ✅ Project Outcome

This project reflects a structured, analytical, and statistically validated EDA pipeline — from raw CSV to conclusive business recommendations. It meets all the objectives outlined by the IBM Capstone and is ideal for inclusion in any data science portfolio.

---

## 📎 Credits

* 🎓 IBM Applied Data Science Capstone (Coursera)
* 📈 Dataset Source: IBM (via project materials)
* 💻 Execution: Python + Google Colab + Matplotlib/Seaborn

---

## 🧠 Author

**Tamaghna Nag**
🔗 [Portfolio](https://tamaghnatech.in) | [LinkedIn](https://www.linkedin.com/in/tamaghna99) | [GitHub](https://github.com/Tamaghnatech)

---

