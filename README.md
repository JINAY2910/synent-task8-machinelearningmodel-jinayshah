# 🏡 House Price Prediction

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

An advanced Machine Learning and Data Science project leveraging regression models to predict **House Prices** using the Boston Housing dataset.

---

## 🎯 Aim & Objectives
- Perform **Data Preprocessing & Cleaning** (handling missing values, formatting features).
- Conduct **Exploratory Data Analysis (EDA)** to identify features highly correlated with house valuation.
- Run **Feature Engineering** to rank the significance of predictors.
- Train and evaluate a **Random Forest Regressor** to predict the target variable `medv` (Median Value of Owner-Occupied Homes).

## 📊 Dataset Used
- **Dataset:** Boston Housing Dataset
- **Source:** Loaded dynamically via online GitHub URL.
- **Key Features Include:**
  - `crim`: Per capita crime rate.
  - `rm`: Average number of rooms per dwelling.
  - `tax`: Full-value property tax rate.
  - `lstat`: Percentage of lower status of the population.
  - `medv` *(Target)*: Median value of owner-occupied homes (in $1000s).

## 🛠️ Tech Stack & Libraries
- **Core:** Python
- **Data Operations:** `pandas`, `numpy`
- **Visualization:** `seaborn`, `matplotlib`
- **Machine Learning:** `scikit-learn` (`RandomForestRegressor`, `train_test_split`, `mean_absolute_error`, `mean_squared_error`, `r2_score`)

---

## 🚀 How to Setup & Run

### 1. Clone the Repository
```bash
git clone https://github.com/JINAY2910/synent-task8-machinelearningmodel-jinayshah.git
cd synent-task8-machinelearningmodel-jinayshah
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the Notebook
```bash
jupyter notebook synent-task8-machinelearningmodel-jinayshah.ipynb
```
Run the notebook to inspect feature importances, target distributions, tree-based regressor evaluations, and error distributions.

---

## 📈 Methodology & Model Insights
1. **Exploratory Visualizations:** Correlation heatmaps and scatter plots highlight strong positive associations with rooms (`rm`) and negative relationships with lower-status population percentage (`lstat`).
2. **Ensemble Modeling:** Selected the powerful **Random Forest Regressor** to capture non-linear relationships and interactions.
3. **Feature Importance:** Ranked factors affecting house values, showing that features like `rm` and `lstat` are dominant predictors.
4. **Performance Evaluation:** Validated predictions using **R² Score**, **Mean Absolute Error (MAE)**, and **Mean Squared Error (MSE)**.

---
*Developed by Jinay Shah*
