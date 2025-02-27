# 📊 Financial Fraud Detection 🔍💰
A Data Analytics project to detect financial fraud using **Python, SQL, and Data Visualization**.

📌 Project Overview
Financial fraud is a major challenge in the banking and e-commerce industries. Fraudulent transactions can lead to huge financial losses, reputational damage, and regulatory penalties. Detecting fraudulent transactions in real-time is crucial to protecting both businesses and customers.

In this project, we analyze financial transactions to identify fraudulent activities using data analytics techniques such as:

Exploratory Data Analysis (EDA)
SQL-based fraud pattern analysis
Correlation heatmap for feature relationships
Time-series fraud trend analysis
Visualization of high-risk merchants and customers
This project demonstrates how data analysis can help in early fraud detection, improving risk management and financial security.

📂 Dataset Information
The dataset consists of 10,000 synthetic financial transactions, including:

Transaction_ID: Unique identifier for each transaction.
Customer_ID: The ID of the customer making the transaction.
Merchant_ID: The ID of the merchant processing the transaction.
Transaction_Type: Whether the transaction was Online, POS (Point-of-Sale), or ATM.
Timestamp: The time at which the transaction occurred.
Amount: The value of the transaction.
IP_Address: The IP address of the transaction (for online transactions).
Is_Fraud: 1 = Fraudulent transaction, 0 = Non-fraudulent transaction.
🔍 Key Objectives
1️⃣ Identify and analyze fraudulent vs. non-fraudulent transactions.
2️⃣ Find high-risk merchants and customers associated with fraud.
3️⃣ Examine fraud transaction patterns based on amount, location, and time.
4️⃣ Perform correlation analysis to determine key fraud indicators.
5️⃣ Use SQL queries to retrieve important fraud insights.
6️⃣ Visualize fraud trends to make data-driven business decisions.

🛠️ Technologies & Tools Used
Python: Data processing & analysis.
Pandas & NumPy: Data manipulation.
Matplotlib & Seaborn: Data visualization.
SQL (SQLite): Fraud pattern extraction.
Jupyter Notebook: Project execution.
Git & GitHub: Version control & project sharing.
📊 Data Analysis & Findings
1️⃣ Fraud vs. Non-Fraud Transaction Distribution
Fraud cases make up only 2% of all transactions, making it an imbalanced dataset.
Fraud detection requires advanced techniques since fraudulent transactions are rare.
2️⃣ Fraudulent Transaction Amounts
Fraudulent transactions tend to have higher amounts than non-fraudulent ones.
The box plot analysis showed that most fraud transactions involve extreme outlier amounts.
3️⃣ High-Risk Merchants & Customers
We identified merchants frequently involved in fraudulent activities.
SQL queries helped find repeat fraud customers, indicating possible stolen or misused accounts.
📌 Correlation Analysis: What Features Are Important?
A correlation heatmap was generated to analyze how different features relate to fraud.

🖥️ Key Findings from Correlation Heatmap
Transaction Amount & Fraud: 💰 Moderate correlation → Higher transactions are slightly more likely to be fraudulent.
Transaction Type (Online, POS, ATM) & Fraud: 🌍 Weak correlation → Fraud is more common in online transactions.
Customer & Merchant IDs: 🔍 Weak correlation → Fraud is spread across different merchants/customers.
🔹 Why This Matters?
Understanding correlations helps in fraud detection models. Features with higher correlation to fraud can be used in machine learning for predictive fraud detection.

📅 Time-Series Analysis of Fraud Trends
Fraudulent transactions were plotted over time to analyze seasonal patterns.

🔹 Key Takeaways:

Certain days showed spikes in fraudulent activities.
Fraud is not random – it follows specific patterns that businesses can monitor.
Time-based fraud detection can help banks flag high-risk transactions immediately.
📈 Visualizations Included
✔ Fraud vs. Non-Fraud Count Plot
✔ Box Plot for Transaction Amounts
✔ Top 10 High-Risk Merchants (Bar Chart)
✔ Top 10 High-Risk Customers (Bar Chart)
✔ Correlation Heatmap for Fraud Features
✔ Time-Series Analysis of Fraud Trends

🏆 Project Insights & Real-World Applications
✅ Early Fraud Detection: Banks can flag high-risk transactions for further investigation.
✅ Preventing Financial Losses: Businesses can set transaction limits for suspicious accounts.
✅ Machine Learning Feature Selection: Correlation insights help in building fraud detection models.
