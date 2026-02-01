# Machine Learning Term Project: LASSO Regression

This project applies **LASSO (Least Absolute Shrinkage and Selection Operator)
regression** to model relationships between a target variable and a set of
predictors while performing **automatic feature selection**.

The goal is to demonstrate how regularization improves model interpretability
and prevents overfitting in high-dimensional settings.

---

## Project Objective
The main objectives of this project are to:
- Build a regression model using LASSO
- Identify the most important predictors by shrinking irrelevant coefficients to zero
- Compare regularized regression with standard linear regression
- Evaluate model performance using appropriate metrics

---

## Dataset
- Dataset provided for academic purposes
- Contains multiple explanatory variables with potential multicollinearity
- Target variable represents the outcome of interest

Preprocessing steps include:
- Handling missing values
- Feature scaling and standardization
- Train–test split for model evaluation

---

## Methodology

### 1. Data Preprocessing
- Cleaning and preparing raw data
- Standardizing features (required for LASSO)
- Separating predictors and target variable

---

### 2. LASSO Regression
- L1-regularized linear regression
- Regularization parameter (λ / alpha) selected via cross-validation
- Coefficients shrunk toward zero to perform feature selection

This allows the model to remain parsimonious while retaining predictive power.

---

### 3. Model Evaluation
- Performance evaluated on unseen test data
- Metrics may include:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² score

Model results are compared to assess the impact of regularization.

---

## Results & Interpretation
- LASSO successfully reduces model complexity
- Only a subset of predictors remains active
- Selected features provide clearer interpretation of key drivers
- Regularization helps mitigate overfitting

---

## Tools & Technologies
- Python
- pandas
- NumPy
- scikit-
