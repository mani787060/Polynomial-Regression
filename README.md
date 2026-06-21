# Polynomial Regression

## 📌 Project Overview

This project demonstrates the implementation of **Polynomial Regression**, a technique used to model non-linear relationships between input features and the target variable.

Using a dataset generated with Scikit-Learn's `make_regression`, the notebook explores how polynomial features can transform a linear model into one capable of capturing curved patterns in data. The project includes both manual polynomial feature creation and implementation using Scikit-Learn's `PolynomialFeatures`.

---

## 🎯 Objectives

* Understand the concept of Polynomial Regression
* Learn how polynomial features are generated
* Compare Linear Regression and Polynomial Regression
* Visualize non-linear relationships in data
* Study the impact of polynomial degree on model performance

---

## 📂 Dataset

**Dataset Used:** `make_regression`

A synthetic regression dataset generated using Scikit-Learn to demonstrate regression modeling and polynomial feature expansion.

---

## 📖 Concepts Covered

* Linear Regression
* Polynomial Regression
* Feature Engineering
* Polynomial Features
* Model Complexity
* Underfitting
* Overfitting
* Regression Analysis

---

## 🛠️ Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## ⚙️ Implementation Steps

### Data Preparation

* Generate regression data using `make_regression`
* Visualize the dataset

### Feature Expansion

* Create polynomial features manually
* Generate polynomial features using `PolynomialFeatures`

### Model Training

* Train Linear Regression on transformed features
* Fit the Polynomial Regression model

### Prediction

* Generate predictions on test data
* Compare linear and polynomial model outputs

### Visualization

* Plot fitted regression curves
* Observe how different polynomial degrees affect the model

---

## 🔍 Key Observations

* Linear Regression struggles to capture non-linear patterns.
* Polynomial features allow linear models to learn curved relationships.
* Higher polynomial degrees increase model flexibility.
* Very high degrees may lead to overfitting.

---

## ✅ Advantages

* Captures complex non-linear relationships
* Easy to implement using feature transformation
* Improves model performance on curved datasets
* Extends the power of Linear Regression

---

## 💻 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## 🏁 Conclusion

Polynomial Regression is a powerful extension of Linear Regression that enables models to learn non-linear patterns through feature transformation. By introducing polynomial terms, it can fit more complex relationships while still using the simplicity of linear models.
