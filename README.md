# 📊 Financial Fraud Detection 🔍💰
A Data Analytics project to detect financial fraud using **Python, SQL, and Data Visualization**.

## 🚀 Project Overview
Fraud detection is critical in the financial industry to prevent **unauthorized transactions and losses**. This project explores financial fraud using **data analysis, SQL queries, and correlation analysis** to identify high-risk transactions.

## 📂 Dataset Information
- **Synthetic dataset** containing 10,000 transactions.
- Includes **customer IDs, merchant IDs, transaction types, amounts, timestamps, and fraud labels (1 = Fraud, 0 = Non-Fraud)**.

## 🛠️ Technologies Used
- **Python** (Pandas, Matplotlib, Seaborn)
- **SQL** (SQLite) for fraud pattern analysis
- **Jupyter Notebook**
- **Git & GitHub** for version control

---

## 📊 **Key Analyses & Findings**

### **1️⃣ Fraud vs. Non-Fraud Transaction Distribution**
- Most transactions are **non-fraudulent**, making fraud detection challenging.
- Fraud cases make up **less than 5%** of all transactions, indicating an **imbalanced dataset**.

### **2️⃣ Fraudulent Transaction Amount Analysis**
- **Boxplot analysis** reveals that **fraudulent transactions tend to have higher amounts** than non-fraudulent ones.
- Some fraud transactions have **outlier amounts**, which could be a key factor in fraud detection.

### **3️⃣ High-Risk Merchants & Customers**
- We identified **merchants with repeated fraud cases** using SQL.
- Some customers **regularly engage in fraudulent activity**, which helps in **risk profiling**.

---

## 🔥 **Understanding the Correlation Analysis**
**Correlation analysis** helps us find **relationships between different features** to understand fraud patterns. 

### 📈 **Correlation Heatmap Findings**
![Correlation Heatmap]

- **Amount vs. Fraud** → Shows **moderate correlation**, meaning that **higher transaction amounts are slightly more likely to be fraudulent**.
- **Merchant_ID & Customer_ID** → Weak correlation with fraud, indicating that **fraud is spread across different merchants and customers**.
- **Transaction_Type (Online, POS, ATM)** → Fraud is **more common in online transactions**, but the correlation is weak.

#### **📌 Why Is Correlation Important?**
- Helps identify **which features influence fraud the most**.
- Assists in **feature selection for machine learning models**.
- Provides insights into **fraudulent transaction patterns**.

---
🏆 Project Insights & Real-World Applications
✅ Early Fraud Detection: Banks can flag high-risk transactions for further investigation.
✅ Preventing Financial Losses: Businesses can set transaction limits for suspicious accounts.
✅ Machine Learning Feature Selection: Correlation insights help in building fraud detection models.
