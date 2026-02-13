🚗 Task 3 – Car Price Prediction
Oasis Infobyte – Data Science Internship
📌 Project Overview

This project involves building a Machine Learning model to predict the selling price of used cars based on various features such as:

Year of manufacture

Present price

Kilometers driven

Fuel type

Transmission type

Ownership history

This is a supervised regression problem.

📊 Dataset Information

The dataset includes:

Numerical features (Year, Present_Price, Driven_kms, Owner)

Categorical features (Fuel_Type, Selling_type, Transmission)

Target variable: Selling_Price

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🔍 Steps Performed
1️⃣ Data Cleaning

Checked for missing values

Removed duplicate records

Performed outlier detection using IQR method

2️⃣ Feature Engineering

Dropped irrelevant column (Car_Name)

Applied One-Hot Encoding for categorical variables

Separated features (X) and target (y)

3️⃣ Model Building

Split dataset into training and testing sets (80/20 split)

Trained a Linear Regression model

4️⃣ Model Evaluation

Evaluated using:

Mean Absolute Error (MAE)

R² Score

Tested prediction using custom sample input

📈 Model Performance

The model achieved a strong R² score, demonstrating good predictive performance for car resale prices.

🧠 Key Learnings

Handling mixed numerical and categorical data

Importance of proper feature encoding

Regression model evaluation

End-to-end ML pipeline development

🚀 Future Improvements

Try Decision Tree / Random Forest Regressor

Hyperparameter tuning

Feature interaction analysis