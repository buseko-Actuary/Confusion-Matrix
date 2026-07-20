<h1 align="center">🌳 Decision Tree vs Logistic Regression</h1>

<p align="center"><b>Two classic classifiers on the Titanic dataset, compared head-to-head — not just which wins, but <i>why</i>.</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"/>
  <img src="https://img.shields.io/badge/Focus-Model%20Comparison-blue?style=flat-square" alt="Model Comparison"/>
  <img src="https://img.shields.io/badge/Metric-Confusion%20Matrix-orange?style=flat-square" alt="Confusion Matrix"/>
</p>

---

## 🎯 The idea

Picking a model isn't just about accuracy — it's about which trade-offs fit the problem. This project runs **Logistic Regression** and a **Decision Tree Classifier** side by side on the same Titanic survival data, so the differences in interpretability, decision boundaries, and error patterns show up directly in the **confusion matrices** rather than a single accuracy number.

## 🔍 What it does

| Step | Detail |
|---|---|
| 🧹 Clean & explore | Titanic dataset — age, sex, class, fare, embarkation |
| 🤖 Train | Fit both Logistic Regression and a Decision Tree on the same features |
| 📊 Evaluate | Confusion matrices + accuracy / precision / recall for each |
| ⚖️ Compare | Statistical, interpretable coefficients vs. rule-based decision boundaries |

## 🛠️ Stack

`Python` · `pandas` · `scikit-learn` (`LogisticRegression`, `DecisionTreeClassifier`, `confusion_matrix`) · `matplotlib / seaborn`

## 📁 File

[`Decision tree (1).ipynb`](Decision%20tree%20(1).ipynb) — full walkthrough from data load to model comparison.

---
<p align="center"><i>Part of my <a href="https://github.com/buseko-Actuary">applied ML & data science portfolio</a> · Buseko · Insight Analytics</i></p>
