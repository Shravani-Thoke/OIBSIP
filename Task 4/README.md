
# 📧 Spam Email Detection

### Oasis Infobyte – Data Science Internship (Task 4)

## 📌 Project Overview

This project focuses on building a Machine Learning model to classify emails as:

* **Spam**
* **Ham (Not Spam)**

The objective is to train a model that can automatically detect spam messages using Natural Language Processing (NLP) techniques.

This is a supervised classification problem involving text data.

---

## 📊 Dataset Information

The dataset contains:

* `v1` → Label (Spam / Ham)
* `v2` → Email message content

Additional unnamed columns were removed during preprocessing as they contained null or irrelevant values.

---

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* TF-IDF Vectorization
* Naive Bayes Classifier

---

## 🔍 Steps Performed

### 1️⃣ Data Cleaning

* Loaded dataset with proper encoding (`latin-1`)
* Removed unnecessary columns (`Unnamed: 2, 3, 4`)
* Mapped target labels:

  * `ham → 0`
  * `spam → 1`

---

### 2️⃣ Text Preprocessing

* Converted text into numerical form using **TF-IDF Vectorization**
* Removed common English stopwords

TF-IDF converts text messages into numerical feature vectors that represent word importance.

---

### 3️⃣ Train-Test Split

* Split dataset into 80% training and 20% testing
* Used `random_state` for reproducibility

---

### 4️⃣ Model Building

* Trained a **Multinomial Naive Bayes** classifier
* Chosen because it performs well for text classification problems

---

### 5️⃣ Model Evaluation

* Evaluated model using **Accuracy Score**
* Achieved high accuracy in distinguishing spam from ham

---

### 6️⃣ Sample Prediction

* Tested the model on a custom email:

  `"Congratulations! You have won a free lottery. Claim now."`

* Model successfully predicted the email as **Spam**

---

## 📈 Model Performance

The Naive Bayes model demonstrated strong performance in classifying spam emails accurately.

---

## 🧠 Key Learnings

* Handling text data in machine learning
* Understanding TF-IDF vectorization
* Applying Naive Bayes for text classification
* End-to-end NLP pipeline implementation
* Binary classification workflow

---

🚀 Future Improvements

* Hyperparameter tuning
* Using Logistic Regression or SVM for comparison
* Implementing confusion matrix and precision-recall metrics
* Deploying as a web application

---

If you want, I can now:

* Write README for Task 5 (Sales Prediction)
* Create one **combined internship README**
* Help you write a strong **Internship Completion LinkedIn post**
* Help you structure your GitHub repository professionally

Just tell me 😊
