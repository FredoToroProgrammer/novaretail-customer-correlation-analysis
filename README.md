# 📊 NovaRetail+ Customer Correlation Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge\&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge\&logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge\&logo=jupyter)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-teal?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

---

# 🚀 Project Overview

NovaRetail+ is a leading e-commerce platform in Latin America with millions of users.

The Growth & Retention team asked:

> **Which customer behavior factors are most strongly associated with annual revenue generated?**

This project uses exploratory correlation analysis to uncover the strongest behavioral drivers of customer value.

---

# 🎯 Objectives

✅ Identify variables associated with revenue
✅ Compare behavioral vs demographic factors
✅ Use proper statistical methods
✅ Generate actionable business insights
✅ Build a portfolio-ready analytics project

---

# 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

---

# 📂 Dataset Features

Main variables analyzed:

| Variable                  | Description              |
| ------------------------- | ------------------------ |
| visitas_mes               | Monthly visits           |
| compras_mes               | Monthly purchases        |
| gasto_publicidad_dirigida | Advertising spend        |
| satisfaccion              | Satisfaction score       |
| miembro_premium           | Premium subscription     |
| abandono                  | Churn                    |
| tipo_dispositivo          | Device type              |
| region                    | Geographic region        |
| ingreso_anual             | Annual revenue generated |

---

# 📈 Key Insights

## 🛒 Purchases drive revenue

* Pearson: **0.967**
* Strongest relationship in the dataset.

## 👀 Visits matter indirectly

* Pearson: **0.337**
* More visits tend to lead to more revenue.

## 📢 Advertising boosts traffic

* Correlation with visits: **0.58**

## ⭐ Premium has low but positive impact

* Point-biserial: **0.093**

## 👥 Demographics matter less

* Age and income showed near-zero correlation.

---

# 📊 Methods Used

* Pearson Correlation
* Spearman Correlation
* Point-Biserial Correlation
* Cramér’s V
* Heatmaps
* Scatterplots

---

# ⚠️ Limitations

* Correlation ≠ causation
* Some variables may be structurally related
* External factors not included
* Results apply to 2024 dataset

---

# 💼 Business Recommendations

✔ Increase purchase frequency
✔ Improve conversion funnels
✔ Optimize advertising ROI
✔ Enhance premium offering
✔ Segment users by behavior

---

# 📁 Repository Structure

```bash
novaretail-customer-correlation-analysis/
│── README.md
│── novaretail_analisis.ipynb
│── requirements.txt
│── data/
│── images/
```

---

# 👤 Author

### Fredy Toro

Aspiring Data Analyst | Building Portfolio Projects 🚀
