# 🩺 Breast Cancer Classification using Logistic Regression

This project implements a **Logistic Regression classification model** to predict whether a breast tumor is **malignant or benign** using the **Breast Cancer dataset**.

The project follows a **standard machine learning workflow**, including data understanding, preprocessing, model training, evaluation, and interpretation.

---

## 📁 Project Structure

Breast_Cancer_Logistic_Regression/<br>
│<br>
├── Breast_Cancer_Logistic_Regression.ipynb # EDA + Logistic Regression model<br>
├── Data.csv # Project documentation<br>
└── README.md # Required Python libraries<br>


---

## 🎯 Project Objective

- Understand the breast cancer dataset and its features<br>
- Perform exploratory data analysis (EDA)<br>
- Build a **Logistic Regression model** for binary classification<br>
- Evaluate model performance using classification metrics<br>
- Interpret model results for medical decision support<br>

---

## 🧠 Problem Type

- **Machine Learning Type:** Supervised Learning  <br>
- **Task:** Binary Classification  <br>
- **Model Used:** Logistic Regression  <br>
- **Target Classes:**  <br>
  - Malignant (Cancerous)  <br>
  - Benign (Non-cancerous)<br>

---

## 🧰 Tools & Technologies Used

### 🔹 Programming Language<br>
- **Python**<br>

### 🔹 Data Analysis & Machine Learning Libraries
- **NumPy**<br>
  - Numerical computations<br>
- **Pandas**<br>
  - Data loading and preprocessing<br>
- **Scikit-learn**<br>
  - `LogisticRegression`
  - `train_test_split`
  - `StandardScaler`
  - Classification metrics<br>

### 🔹 Visualization Libraries
- **Matplotlib**<br>
- **Seaborn**<br>

### 🔹 Development Environment
- **Jupyter Notebook**<br>

---

## 📊 Dataset Information

- **Dataset:** Breast Cancer Dataset  <br>
- **Source:** Kaggle Data <br>
- **Type:** medical dataset  <br>
- **Features Include:**<br>
  - Mean radius, texture, perimeter, area<br>
  - Smoothness, compactness, concavity<br>
  - Symmetry and fractal dimensions<br>

The dataset is widely used for **binary classification and medical ML research**.<br>

---

## 🔍 Workflow

### 1️⃣ Data Understanding & EDA
- Dataset inspection using `info()`, `describe()`<br>
- Target class distribution analysis<br>
- Correlation analysis between features<br>

### 2️⃣ Data Preprocessing
- Feature-target separation<br>
- Train-test split<br>
- Feature scaling using **MinMaxScaler**<br>

### 3️⃣ Model Building
- Logistic Regression model trained on scaled data<br>
- Model learns probability of malignancy<br>

### 4️⃣ Model Evaluation
Model performance evaluated using:<br>
- Accuracy Score<br>
- Confusion Matrix<br>
- Precision<br>
- Recall<br>
- F1-Score<br>

### 5️⃣ Visualization & Interpretation
- Confusion matrix visualization<br>
- Feature influence understanding<br>
- Model performance interpretation<br>

---

## 📈 Key Insights

- Logistic Regression performs effectively for binary medical classification<br>
- Feature scaling significantly improves model stability<br>
- The model provides interpretable results suitable for healthcare use-cases<br>
- High recall is crucial to minimize false negatives in cancer detection<br>

---

## 🎯 Learning Outcomes

- Strong understanding of **Logistic Regression**<br>
- Hands-on experience with classification metrics<br>
- Medical dataset handling and preprocessing<br>
- Feature scaling importance in ML models<br>
- End-to-end ML classification workflow<br>

---

## ⚠️ Disclaimer

This project is developed **strictly for educational and learning purposes**.  <br>
It should **not** be used as a medical diagnostic tool or for clinical decision-making.<br>

---

## Author
**Abbu Talib Ansari**<br>
GitHub:https://github.com//talibansari1914//Breast_Cancer_Prediction_LogisticRegression_Model<br>

⭐ This project demonstrates applied machine learning using Logistic Regression in the healthcare domain.
