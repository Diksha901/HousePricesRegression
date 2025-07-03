# 🏠 House Prices Prediction (Regression)

This project focuses on predicting house prices using machine learning regression models, including **Decision Tree Regressor**, **Random Forest Regressor**, **XGBoost Regressor**, and a **Stacked Ensemble** model. The dataset used is based on housing data with various features describing the properties.

---

## 📁 Files in This Repository

- `HousePricesRegression.ipynb` — Jupyter Notebook with data preprocessing, model training, evaluation, and visualization.
- `train.csv` — Training dataset with features and target (`SalePrice`).
- `test.csv` — Test dataset (optional, if Kaggle format).
- `README.md` — You’re reading it!

---

## 🧠 Models Used

1. **Decision Tree Regressor**
   - Basic model to understand decision-based splits.
   - Prone to overfitting but useful for baseline.

2. **Random Forest Regressor**
   - Ensemble of Decision Trees using bagging.
   - Reduces variance and improves generalization.

3. **XGBoost Regressor**
   - Gradient boosting algorithm for high performance.
   - Handles missing data and feature importance well.

4. **Stacked Regressor (Ensemble)**
   - Combines predictions from the above models .
   - Yielded improved performance.

---

## 📊 Evaluation Metrics

- **R² Score**
- Cross-validation scores for model stability

---

## 🛠️ Libraries Used

- `pandas`, `numpy` — Data processing
- `matplotlib`, `seaborn` — Data visualization
- `scikit-learn` — ML models, preprocessing, and evaluation
- `xgboost` — XGBoost Regressor
  

---


