# Task 3: Linear Regression

## Objective
Implement and understand **Simple** and **Multiple Linear Regression** using Python.

---

## Tools Used
- [Scikit-learn]
- [Pandas]
- [Matplotlib]

---

## Project Steps

1. **Import and Preprocess the Dataset**  
   - Load the dataset using Pandas.
   - Check for missing values and basic statistics.
   - Select appropriate feature(s) and target variable (`price`).

2. **Split Data into Train-Test Sets**  
   - Use `train_test_split` from scikit-learn to divide data (e.g., 80% training, 20% testing).

3. **Fit a Linear Regression Model**  
   - Use `LinearRegression` from `sklearn.linear_model`.
   - Fit the model on the training data.

4. **Evaluate the Model**  
   - Predict using the test set.
   - Calculate:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R-squared score (R²)

5. **Plot Regression Line and Interpret Coefficients**  
   - Plot actual vs predicted values.
   - Draw the regression line.
   - Interpret model intercept and feature coefficients.

---

