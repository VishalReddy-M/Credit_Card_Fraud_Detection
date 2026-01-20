# Credit_Card_Fraud_Detection
# 💳 Credit Card Fraud Detection using Logistic Regression

## 📌 Project Overview
Credit card fraud is a major issue in the financial sector, causing significant monetary losses every year.  
This project aims to **detect fraudulent credit card transactions** using **Logistic Regression**, a widely used and interpretable machine learning classification algorithm.

The model is trained on transaction data containing multiple numerical features and predicts whether a transaction is **fraudulent (1)** or **legitimate (0)**.

---

## 🎯 Objectives
- Analyze and understand transaction patterns
- Handle highly **imbalanced data**
- Build a **Logistic Regression** classification model
- Evaluate model performance using appropriate metrics
- Reduce false negatives to minimize undetected fraud

---

## 📂 Dataset
- The dataset contains **anonymized numerical features** derived from PCA
- Total features: **29**
- Target column: **Class**
  - `0` → Legitimate transaction  
  - `1` → Fraudulent transaction
- The dataset is **highly imbalanced**, with fraud cases being very rare

> ⚠️ Due to privacy concerns, original feature names are not provided.

---

## 🛠️ Technologies & Tools Used
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib / Seaborn**
- **Scikit-learn**
- **VS Code**

---

## 🔍 Workflow
1. **Data Loading**
2. **Exploratory Data Analysis (EDA)**
3. **Data Preprocessing**
   - Handling class imbalance
   - Feature scaling using StandardScaler
4. **Train-Test Split**
5. **Model Building**
   - Logistic Regression
6. **Model Evaluation**
   - Confusion Matrix
   - Accuracy
  

---

## 📈 Model Used
### Logistic Regression
- Suitable for binary classification
- Fast and interpretable
- Works well with scaled numerical data
- Helps understand feature importance through coefficients

---

## 📊 Evaluation Metrics
Since the dataset is imbalanced, accuracy alone is not sufficient.  
The model is evaluated using:
- **Accuracy Score**

> Special focus is given to **Recall**, as detecting fraudulent transactions is more critical than misclassifying legitimate ones.

---

## 🚀 Results
- The model successfully identifies fraudulent transactions
- Achieves strong recall with acceptable precision
- Demonstrates Logistic Regression as a reliable baseline model for fraud detection

---

## 📁 Project Structure
