# 🏥 Medical Insurance Cost Prediction using Linear Regression

This project focuses on building a predictive Machine Learning model using the **Medical Cost Personal Dataset**. It demonstrates data preprocessing, handling categorical features with One-Hot Encoding, feature scaling, training a **Linear Regression** model, and visualizing actual vs predicted results.

---

## 🛠️ Project Workflow & Steps
1. **Data Loading & Exploration:** Loaded the dataset (`insurance.csv`) and analyzed columns like age, BMI, smoking habits, and charges.
2. **Data Preprocessing & Pipelines:** 
   * Used **StandardScaler** for numerical features (`age`, `bmi`, `children`).
   * Used **OneHotEncoder** for categorical features (`sex`, `smoker`, `region`) via `ColumnTransformer`.
   * Built an end-to-end scikit-learn **Pipeline** to prevent data leakage and streamline execution.
3. **Model Training:** Trained a **Linear Regression** model on 80% of the data.
4. **Model Evaluation:** Evaluated performance using **Root Mean Squared Error (RMSE)** and **$R^2$ Score**.
5. **Data Visualization:** Plotted an **Actual vs Predicted** scatter plot with a perfect-fit reference line to check model accuracy.

---

## 📊 Model Performance

| Metric | Score |
| :--- | :---: |
| **$R^2$ Score** | **0.7836** |
| **RMSE** | **5,796.28** |

---

## 📦 Tech Stack & Libraries
* **Python**
* **Pandas & NumPy** (Data Manipulation)
* **Scikit-Learn** (Preprocessing, Pipelines, Linear Regression, Metrics)
* **Matplotlib & Seaborn** (Data Visualization)

---
