# California Housing Price Prediction 🏡
---
This project analyzes and models housing prices in California using the `fetch_california_housing` dataset from Scikit-learn. The goal is to predict median house values based on various demographic and geographic features.

## 🔧 Tools & Libraries
---
- Python
- Pandas, NumPy, Matplotlib
- Scikit-learn (`LinearRegression`, `StandardScaler`, `Pipeline`, `train_test_split`)

## 📊 Workflow Summary
---
1. **Data Loading**: Used built-in California housing dataset as a DataFrame.
2. **EDA**: Visualized housing prices on a Lat-Long scatterplot.
3. **Preprocessing**: Removed redundant columns
4. **Modeling**: Trained a pipeline with `StandardScaler` and `LinearRegression`.
5. **Evaluation**:
   - Used RMSE to evaluate performance.
   - Compared training vs test RMSE to check overfitting.
   - Plotted predicted vs actual prices.

## ✅ Result
---
- RMSE on Train and Test sets are close → low overfitting.
- Model captures broad trends but may miss non-linear patterns.
---

> Lightweight regression pipeline showcasing geospatial regression on real-world data.
