# ☕ Coffee Sales Data Analysis & Prediction

## 📌 Overview

This project focuses on analyzing and predicting coffee sales using a dataset that includes features like product types, regions, sales volumes, and revenue. The goal is to uncover trends and build regression models that accurately forecast sales performance across different categories.

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA) on coffee sales.
- Identify top-performing products, regions, and revenue trends.
- Build regression models to predict future sales.
- Compare model performance using R² and RMSE metrics.

---

## 🗃️ Dataset

- Source: Local CSV file (`index.csv`)
- Key Features:
  - `Product`, `Region`, `Revenue`, `Profit`
  - `Date`, `Customer Type`, `Sales Volume`

---

## 🔍 Exploratory Insights

- Sales trends visualized over time using **Plotly** and **Seaborn**.
- Comparison of sales by:
  - Product category
  - Region
  - Customer segment
- Correlation heatmaps and distribution plots used to detect patterns.

---

## 🤖 Machine Learning Models Used

| Model                     | Evaluation Metric |
|--------------------------|-------------------|
| Linear Regression         | R², RMSE          |
| Decision Tree Regressor   | R², RMSE          |
| Random Forest Regressor   | R², RMSE          |
| Gradient Boosting         | R², RMSE          |
| XGBoost Regressor         | ✅ Best accuracy   |

> StandardScaler and OneHotEncoding were applied for preprocessing.

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:**
  - `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
  - `scikit-learn`, `xgboost`

---

