
# Car Price Prediction: Regression Model Evaluation

## 📌 Overview
This project focuses on evaluating different regression models for predicting car prices over time. The analysis is performed using a Jupyter Notebook in Google Colab, and the results are visualized through scatter plots comparing actual vs. predicted prices.

---

## 📊 Models Evaluated
The following models are included in the evaluation:

- **Linear Regression**
- **Polynomial Regression (PolynomialFeatures)**
- **Decision Tree Regressor**

Each model is tested on historical car price data, and predictions are compared against actual values.

---

## 🔍 Visualizations
The notebook generates comparison plots for each model:

- **Top Left:** Linear Regression
- **Top Right:** Linear Regression (alternative configuration)
- **Bottom Left:** Polynomial Regression
- **Bottom Right:** Decision Tree Regression

**Plot Details:**
- **Blue dots:** Actual prices
- **Red dots:** Predicted prices
- **X-axis:** Year
- **Y-axis:** Price

---

## 🛠 Requirements
To run this project, you need:
- Python 3.x
-  Google Colab
- Libraries:
  - NumPy
  - Pandas
  - Matplotlib
  - Scikit-learn

---


## 📈 Key Insights
- **Linear Regression** provides a baseline performance.
- **Polynomial Regression** captures non-linear trends better.
- **Decision Tree Regressor** adapts well to complex patterns but may overfit.

---

## ✅ Future Enhancements
- Add advanced models (Random Forest, Gradient Boosting)
- Perform hyperparameter tuning
- Implement cross-validation
- Explore feature engineering for improved accuracy
