# 🚨 An Anomaly: Fraud Detection using ML & Power BI

## 📌 Overview
This project simulates a real-world fraud detection monitoring system by combining machine learning predictions with an interactive Power BI dashboard.

## 🧠 Problem Statement
Fraud detection datasets are highly imbalanced, making traditional metrics like accuracy misleading. The goal is to evaluate how well a model detects fraudulent transactions.

## ⚙️ Approach
- Built a machine learning model in Google Colab
- Generated predictions (Fraud vs Normal)
- Imported results into Power BI
- Designed a 2-page dashboard for performance evaluation

## 📊 Key Metrics
- Precision: 0.72  
- Recall: 0.22  
- F1 Score: 0.34  
- False Positives: 8  
- False Negatives: 73  

## 🔍 Key Insights
- The model has high precision but very low recall  
- ~78% of fraud cases are missed  
- Indicates the model is too conservative in detecting fraud  

## 💼 Business Impact
Missing fraud cases can lead to significant financial loss.  
Improving recall is more critical than minimizing false positives in fraud detection systems.

## 📸 Dashboard Preview

### Overview Dashboard
![Overview](screenshots/overview-dashboard.png)

### Model Performance Deep Dive
![Deep Dive](screenshots/model-performance-deep-dive.png)

## 🚀 Tech Stack
- Python (Scikit-learn, Pandas, NumPy)
- Power BI
- Google Colab

## 📌 Future Improvements
- Improve recall using threshold tuning
- Experiment with advanced models (XGBoost, Isolation Forest)
- Handle class imbalance using SMOTE

---
