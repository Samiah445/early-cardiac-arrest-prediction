# 🫀 Early Cardiac Arrest Alert System
### Real-Time Prediction using LSTM (Team Project)

## 👥 Team Project
This project was developed as part of the Machine Learning course (AI3201T) at Umm Al-Qura University.

Supervisor: Dr. Afaf Almehmadi  
Course: Machine Learning – AI3201T  
Semester: 1st Semester 2025  

---

## 📌 Overview
This project presents a real-time intelligent system for early prediction of cardiac arrest in emergency departments.

The system continuously monitors patient vital signs:
- Heart Rate
- Blood Pressure
- Oxygen Saturation (SpO2)
- Respiratory Rate
- Body Temperature

A Long Short-Term Memory (LSTM) model is used to analyze time-series data and predict cardiac arrest 10–30 minutes before occurrence.

---

## 🎯 Objectives
- Early detection of high-risk patients  
- Reduce response time in emergency situations  
- Provide explainable predictions using SHAP  
- Improve patient survival rates  

---

## 🧠 Methodology
- Data preprocessing (handling missing values & noise)
- Time-series modeling using LSTM
- Sliding window sequences (T=5)
- Class imbalance handling
- Early stopping to avoid overfitting
- SHAP for model interpretability

---

## ⚙️ Features
- Real-time monitoring system  
- Early prediction (10–30 minutes ahead)  
- Multi-variable input (vital signs + demographics)  
- Explainable AI (feature importance)  
- Alert system for medical staff  

---

## 📊 Results
- Accuracy: 98.3%
- ROC-AUC: 0.999
- Strong precision and recall for both classes
- Minimal misclassification

⚠️ Note: Results may be optimistic due to synthetic dataset usage.

---

## ⚠️ Limitations
- Synthetic dataset (limited real-world data)
- Possible overfitting
- Requires continuous accurate vital signs
- Limited generalizability across hospitals

---

## 🚀 Future Work
- Use real multi-hospital datasets  
- Integrate with hospital monitoring systems  
- Build web/mobile dashboard  
- Improve generalization and reduce false alerts  

---

## 📄 Full Report
👉 See full project report: report.pdf

---

## 🎯 My Contribution (Samia AlMalki)
- Worked on LSTM model development for time-series prediction  
- Data preprocessing and feature engineering  
- Contributed to model evaluation and performance analysis  

---

## 📚 References
Key references include research on:
- Cardiac arrest prediction using ML  
- LSTM for time-series healthcare data  
- SHAP explainability  

(See full list in report.pdf)
