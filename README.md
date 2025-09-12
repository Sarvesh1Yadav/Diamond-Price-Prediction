# 💎 Diamond Price Prediction

## 📌 Objective
To build a predictive model that estimates diamond prices based on features such as **carat, cut, clarity, and color**, enabling data-driven valuation for buyers and sellers.

---

## 🔍 Approach
- Conducted **Exploratory Data Analysis (EDA)** to study relationships between diamond attributes and price.
- Built **data preprocessing pipelines** with imputation, scaling, and encoding.
- Implemented and compared multiple regression models:
  - Linear Regression  
  - Lasso Regression  
  - Ridge Regression  
  - ElasticNet Regression  
  - Decision Tree Regressor  
- Evaluated models using **MAE, RMSE, and R² Score**.

---

## 📊 Results
| Model                | MAE    | RMSE       | R² Score |
|-----------------------|--------|------------|----------|
| Linear Regression     | ~675   | ~1,026,734 | 0.937    |
| Lasso Regression      | ~676   | ~1,026,849 | 0.937    |
| Ridge Regression      | ~675   | ~1,026,735 | 0.937    |
| ElasticNet Regression | ~1064  | ~2,350,185 | 0.856    |
| Decision Tree         | ~0.37  | ~81        | 0.999*   |

> ⚠️ *Decision Tree achieved near-perfect R² on training data, indicating **overfitting**. Regularization or ensemble methods (Random Forest, XGBoost) would be used in practice to improve generalization.*

---

## 🚀 Impact
- Achieved **R² ≈ 0.94** with Linear, Ridge, and Lasso regression models.  
- Demonstrated that diamond prices can be effectively predicted from their physical attributes.  
- Provides a data-driven approach for buyers and sellers to make **informed pricing decisions**.  

---

## 🛠️ Tech Stack
- **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn)
- **Jupyter Notebook** for analysis and model building

---

---

## 📌 Next Steps
- Apply **cross-validation** to better assess model performance.  
- Explore **ensemble methods (Random Forest, XGBoost)** for improved accuracy.  
- Deploy as a **Flask/Streamlit web app** for interactive price prediction.  

---

