# Fraud Detection using Machine Learning

## 📌 Overview
This project aims to develop a **machine learning model** for detecting fraudulent financial transactions. The dataset consists of over **6.3 million transactions** with various attributes, including transaction type, amount, origin and destination accounts, and fraud indicators. The primary objective is to **proactively identify fraudulent activities** and provide actionable insights for financial security.

---

## 📂 Dataset
The dataset contains **6,362,620 rows** and **10 columns**, including:

- **`step`**: Represents the time in hours (1 step = 1 hour, total 30 days of simulation).
- **`type`**: Type of transaction (`CASH-IN`, `CASH-OUT`, `DEBIT`, `PAYMENT`, `TRANSFER`).
- **`amount`**: Transaction amount in local currency.
- **`nameOrig`**: Customer who initiated the transaction.
- **`oldbalanceOrg`**: Initial balance of the sender before the transaction.
- **`newbalanceOrig`**: Balance of the sender after the transaction.
- **`nameDest`**: Recipient of the transaction.
- **`oldbalanceDest`**: Initial balance of the recipient before the transaction.
- **`newbalanceDest`**: Balance of the recipient after the transaction.
- **`isFraud`**: Indicator of whether the transaction was fraudulent.
- **`isFlaggedFraud`**: Flags illegal attempts for large transfers (> 200,000 per transaction).

---

## 🎯 Objectives
- ✅ Perform **data cleaning**, handling missing values, outliers, and multi-collinearity.
- ✅ Develop a **fraud detection model** using machine learning techniques.
- ✅ Identify **key factors** predicting fraudulent transactions.
- ✅ Demonstrate **model performance** using appropriate evaluation metrics.
- ✅ Provide **recommendations** for fraud prevention strategies.

---

## 🛠️ Approach
### 1️⃣ Data Cleaning
- Identified and handled **missing values**.
- Detected and removed **outliers**.
- Addressed **multi-collinearity** among variables.

### 2️⃣ Exploratory Data Analysis (EDA)
- **Visualized transaction distributions**.
- Analyzed **fraud trends** based on transaction types and amounts.

### 3️⃣ Feature Engineering
- Derived **new features** to improve model performance.
- Normalized **transaction amounts** to remove bias.

### 4️⃣ Model Development
- Implemented various **machine learning models**:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost
  - Neural Networks
- **Optimized hyperparameters** to enhance performance.

### 5️⃣ Model Evaluation
- Used **Precision, Recall, F1-score, and ROC-AUC** to assess model accuracy.
- Compared models to identify the **best-performing one**.

### 6️⃣ Fraud Prevention Strategies
- Suggested **real-time monitoring tools**.
- Recommended **anomaly detection methods**.
- Proposed **AI-driven fraud detection systems**.

---

## 📊 Results & Insights
- **High-value transfers** and **cash-out transactions** were common in fraudulent activities.
- **Imbalanced fraud distribution** required advanced resampling techniques.
- The **Random Forest** and **XGBoost** models performed best in detecting fraudulent transactions.

---

## 🚀 Future Work
- Implement **deep learning techniques** for further improvement.
- Deploy the model as an **API for real-time fraud detection**.
- Enhance **feature selection** for better fraud pattern recognition.

---

## 🏗️ How to Use
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Fraud-Detection-ML.git
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook Fraud_Detection.ipynb
   ```
4. **Follow the notebook** for step-by-step implementation.

---

## 🤝 Contributing
Contributions are welcome! Feel free to **open issues** or **submit pull requests**.

---

## 📜 License
This project is open-source and available under the **MIT License**.

---

## ✍️ Author
**Omkar Mahadev Bhandavalakar**

