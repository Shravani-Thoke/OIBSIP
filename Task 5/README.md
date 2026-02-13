# 📊 Sales Prediction Using Machine Learning

### Oasis Infobyte – Data Science Internship (Task 5)

## 📌 Project Overview

This project focuses on predicting product sales based on advertising expenditures across different platforms.

The objective is to understand how advertising investments in various media channels influence product sales and to build a regression model that can accurately predict future sales.

This is a supervised regression problem.

---

## 📊 Dataset Information

The dataset contains advertising budgets and corresponding sales figures:

* **TV** – Advertising budget spent on TV
* **Radio** – Advertising budget spent on Radio
* **Newspaper** – Advertising budget spent on Newspaper
* **Sales** – Target variable (product sales)

The dataset was clean and required minimal preprocessing.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Linear Regression

---

## 🔍 Steps Performed

### 1️⃣ Data Preprocessing

* Loaded dataset
* Checked for missing values
* Removed unnecessary index column (`Unnamed: 0`)

---

### 2️⃣ Feature & Target Separation

* Defined:

  * `X` → Advertising budgets (TV, Radio, Newspaper)
  * `y` → Sales

---

### 3️⃣ Train-Test Split

* Split data into 80% training and 20% testing sets
* Used `random_state` for reproducibility

---

### 4️⃣ Model Building

* Trained a **Linear Regression** model
* The model learns the relationship:

[
Sales = w_1(TV) + w_2(Radio) + w_3(Newspaper) + b
]

---

### 5️⃣ Model Evaluation

* Evaluated performance using:

  * **Mean Absolute Error (MAE)**
  * **R² Score**

These metrics measure prediction accuracy and how well the model explains variance in sales.

---

## 📈 Model Performance

The Linear Regression model demonstrated strong predictive capability, showing that advertising spend significantly impacts sales performance.

---

## 🧠 Key Learnings

* Understanding regression problems
* Feature-target separation
* Model training and evaluation
* Interpreting regression metrics (MAE & R²)
* Building an end-to-end ML pipeline

---

## 🚀 Future Improvements

* Polynomial Regression for nonlinear relationships
* Feature scaling
* Comparing with Decision Tree & Random Forest models
* Residual analysis

---

## 📌 Conclusion

This project demonstrates how machine learning can be used in marketing analytics to predict sales based on advertising investment.

It strengthens foundational knowledge in regression modeling and business data analysis.

