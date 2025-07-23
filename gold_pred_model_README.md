# 🟡 Gold Price Prediction using Machine Learning

> 📈 Predicting gold prices using financial indicators and temporal feature engineering — achieved ~93% R² accuracy.

---

## 📌 Overview
This project focuses on building a machine learning model to predict gold prices (`GLD`) using economic indicators and **date-based features** like `Month`, `Day`, and `Weekday`.

With thoughtful preprocessing and feature engineering, the final model achieved **~93% accuracy (R² score)** — showing how data understanding can drive better results.

---

## 🧠 Objectives
- Clean and preprocess financial time series data
- Visualize data distributions and detect outliers
- Extract **temporal features** from the `Date` column
- Build and evaluate regression models for gold price prediction
- Use multiple metrics to measure model performance

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 📂 Dataset
- File: `gld_price_data.csv`
- Features: `Date`, `SPX`, `GLD`, `USO`, `SLV`, `EUR/USD`

---

## 🔍 Key Steps
- Performed **EDA**: distributions, boxplots
- Treated outliers using **IQR method**
- Engineered features from `Date`: `Month`, `Day`, `Weekday`
- Built a **Linear Regression** model
- Evaluated using:
  - R² Score: ~0.93
  - MAE, MSE, RMSE

---

## ✅ Results
- Model performed well on test data with high R² score
- Date-based features significantly boosted model accuracy
- All metrics indicate strong predictive performance

---

## 🧠 Learnings
- Even simple features like `Month` or `Weekday` can hold powerful predictive signals in financial data
- Good feature engineering can often outperform model complexity

---

## 🚀 How to Run
1. Clone this repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
