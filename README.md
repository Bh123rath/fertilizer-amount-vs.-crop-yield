
# 🌾 Polynomial Regression: Fertilizer vs Crop Yield

This project demonstrates how to use **Polynomial Regression** with Python to model the relationship between **fertilizer application (kg/hectare)** and **crop yield (tons/hectare)**.

## 🚀 Tech Stack

* **Python**
* **NumPy & pandas** → Data handling
* **Matplotlib** → Data visualization
* **scikit-learn** → Polynomial regression model

## 📊 Workflow

1. Load dataset from an Excel file (`Fertilizers.xlsx`).
2. Extract independent variable (`Fertilizer`) and dependent variable (`Yield`).
3. Apply `PolynomialFeatures(degree=2)` to include quadratic terms.
4. Fit a `LinearRegression` model on the transformed data.
5. Visualize results:

   * Blue scatter points → actual data
   * Red curve → polynomial regression fit

## 📷 Output

The model produces a curve that captures **non-linear growth patterns**, providing a more realistic picture of how fertilizer impacts yield compared to simple linear regression.

