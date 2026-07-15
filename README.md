# Decision Tree vs Logistic Regression — Model Comparison

Comparing two classic classification algorithms — **Logistic Regression** and a **Decision Tree Classifier** — on the Titanic survival dataset, to understand not just which performs better but *why*.

## What this covers

- Data cleaning and exploratory analysis on the Titanic dataset (age, sex, class, fare, embarkation, etc.)
- Training both a Logistic Regression model and a Decision Tree Classifier on the same features
- Evaluating both with **confusion matrices** and standard classification metrics (accuracy, precision, recall)
- Comparing the two approaches: Logistic Regression's statistical, interpretable coefficients vs. the Decision Tree's rule-based, visual decision boundaries

## Why this comparison matters

Picking a model isn't just about accuracy — it's about which trade-offs fit the problem. This project walks through both approaches side by side on the same data so the differences in interpretability, decision boundaries, and error patterns are directly visible in the confusion matrices rather than just a single accuracy number.

## Stack

Python · pandas · scikit-learn (LogisticRegression, DecisionTreeClassifier, confusion_matrix) · matplotlib/seaborn

## File

`Decision tree (1).ipynb` — full walkthrough from data load to model comparison.
