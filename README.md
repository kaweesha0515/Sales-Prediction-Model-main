# 📊 Sales Prediction Model

## 🚀 Project Overview
This machine learning project aims to predict product sales based on advertising budgets allocated across various media channels, including **TV**, **Radio**, and **Newspaper**. It explores the effectiveness of different regression models and highlights the importance of each feature in driving sales.

## 📂 Dataset
- **Source:** [Kaggle - Advertising Dataset](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)
- **Features:**
  - `TV`: Budget spent on TV advertisements
  - `Radio`: Budget spent on radio advertisements
  - `Newspaper`: Budget spent on newspaper advertisements
- **Target:** `Sales`: Units sold

## 🎯 Objectives
- Predict sales using supervised regression models
- Compare the accuracy of multiple regression techniques
- Visualize correlations and feature importance

## 🛠️ Methodology
1. **Exploratory Data Analysis (EDA)**
2. **Data Cleaning & Preprocessing**
3. **Model Development:**
   - Linear Regression
   - Random Forest Regression
   - Voting Regressor (Ensemble Learning)

## 🧰 Libraries Used
- `pandas` – data manipulation
- `numpy` – numerical computations
- `scikit-learn` – machine learning
- `matplotlib` & `seaborn` – data visualization

## 📈 Model Performance
| Metric | Score |
|--------|-------|
| Mean Absolute Error (MAE) | **0.83** |
| Mean Squared Error (MSE)  | **1.02** |
| Root Mean Squared Error (RMSE) | **1.01** |

## 📊 Visualizations
- 🔥 **Correlation Heatmap**: Shows relationship strength between variables
- ⭐ **Feature Importance Plot**: Highlights which ad platforms impact sales most

## 🔮 Future Improvements
- Implement hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
- Evaluate additional models like XGBoost, Lasso, and Ridge Regression
- Add cross-validation and outlier detection for improved generalization

## 📬 Contact
📧 **Email:** kaweeshawickrama@gmail.com

---

> 📌 *This project is a demonstration of applied data science for business intelligence and can be extended for real-world retail prediction pipelines.*
