# FraudShield: Transaction Anomaly Detection System

## 📌 Overview
FraudShield is a **machine learning-based fraud detection system** designed to identify suspicious financial transactions with high accuracy. By leveraging **XGBoost, Decision Trees, Logistic Regression, and anomaly detection techniques** like **Isolation Forest and Local Outlier Factor (LOF)**, this system ensures robust fraud prevention in real-time payment environments.

## 🚀 Key Features
- **Multi-Model Approach:** Utilizes **XGBoost, Decision Trees, and Logistic Regression** to classify fraudulent transactions.
- **Anomaly Detection:** Implements **Isolation Forest and LOF** to detect unusual transaction patterns.
- **Feature Engineering:** Extracts transaction-based features such as **amount variations, balance fluctuations, and entity behaviors**.
- **High Accuracy:** Achieves **98.89% accuracy** in fraud detection.
- **Scalable Pipeline:** Designed for real-time fraud prevention in **financial applications**.

## 📊 Dataset
- **Source:** The dataset consists of financial transactions labeled as fraudulent or non-fraudulent.
- **Size:** ~6.3 million transactions with **11 features**.
- **Key Columns:**
  - `amount`: Transaction amount.
  - `oldbalanceOrg`, `newbalanceOrig`: Sender’s balance before and after the transaction.
  - `oldbalanceDest`, `newbalanceDest`: Receiver’s balance before and after the transaction.
  - `isFraud`: Label indicating fraudulent transactions.

## 🔍 Machine Learning Models Used
1. **XGBoost**: Optimized for high-performance classification.
2. **Decision Trees**: Provides interpretability in fraud decision-making.
3. **Logistic Regression**: Baseline model for fraud probability estimation.
4. **Isolation Forest & LOF**: Detect anomalies by identifying transactions that deviate from normal behavior.

## ⚙️ Model Performance
- **Accuracy:** 98.89%
- **F1 Score & ROC AUC:** Evaluated to measure precision and recall balance.
- **Feature Importance Analysis:** Transaction amount, balance fluctuations, and entity-specific behaviors were key indicators.

## 📌 How to Run the Project
### 1️⃣ Clone the Repository
```bash
 git clone https://github.com/Soniaranvir/fraud-shield-detection.git
 cd fraud-shield-detection
```

### 2️⃣ Install Dependencies
```bash
 pip install -r requirements.txt
```

### 3️⃣ Run the Model
```python
 python fraud_detection.py
```

## 📌 Future Enhancements
- Integration with **real-time streaming frameworks** (Apache Kafka).
- Deployment using **AWS Lambda or Vertex AI**.
- Advanced deep learning techniques for improved fraud detection.

---

