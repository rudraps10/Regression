# 🛍️ E-commerce Spending Prediction using Linear Regression

This project uses a real-world E-commerce customer dataset to predict **Yearly Amount Spent** by customers using Linear Regression. The goal is to build a model that helps an e-commerce company understand which user behavior metrics most affect spending.

---

## 📊 Problem Statement

The company wants to understand customer behavior and improve marketing strategies.  
Using customer data like time spent on the app, website, membership duration, and more — we predict how much they are likely to spend annually.

---

## 🧠 What I Learned

- Exploratory Data Analysis (EDA)
- Seaborn visualizations (pairplot, heatmap, scatterplots)
- Correlation and feature importance
- Model training with `sklearn.linear_model.LinearRegression`
- Model evaluation using:
  - R² Score
  - Root Mean Squared Error (RMSE)
  - Residual plots (Actual vs Predicted)

---

## 📁 Dataset

- File: `Ecommerce Customers.csv`
- Columns:
  - `Avg. Session Length`
  - `Time on App`
  - `Time on Website`
  - `Length of Membership`
  - `Yearly Amount Spent` (Target)

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Seaborn + Matplotlib
- Scikit-learn

---

## 📈 Model Training

```python
from sklearn.linear_model import LinearRegression
lm = LinearRegression()
lm.fit(X_train, y_train)
predictions = lm.predict(X_test)
