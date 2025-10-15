# 🎓 Student Stress Level Prediction  

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)]()  
[![scikit-learn](https://img.shields.io/badge/Machine%20Learning-scikit--learn-orange)]()  
[![License](https://img.shields.io/badge/License-MIT-green)]()  

---

## 🧠 Introduction  

This project focuses on predicting **student stress levels** using **machine learning techniques**.  
Stress is a growing concern among students, impacting both **academic success** and **mental well-being**.  
The goal is to understand and forecast stress patterns using various behavioral, academic, and health factors.  

We aim to answer:  
- Can machine learning **accurately predict** stress levels?  
- Which **features contribute most** to student stress?  
- How do different algorithms compare in terms of performance?  

---

## 🎯 Project Goals  

- Perform **exploratory data analysis (EDA)** to uncover patterns.  
- Develop a **baseline model** for comparison.  
- Train and evaluate **Logistic Regression**, **Decision Tree**, and **Random Forest** models.  
- Measure results using **accuracy, F1-score, and confusion matrices**.  
- Identify **important predictors** influencing stress.  

---

## 📂 Dataset Description  

- Approximately **1100 entries** of student data.  
- Around **20 attributes** covering health, academic, and lifestyle metrics.  
- Target variable: `stress_level` (categorical).  
- Dataset is **balanced** and has **no major missing values**.  

> ⚠️ *Dataset not included due to licensing. Please replace `student_stress.csv` with your local dataset.*  

---

## 💻 Tools & Technologies  

- **Programming Language:** Python (v3.9+)  
- **Key Libraries:**  
  - `pandas`, `numpy` → data manipulation  
  - `matplotlib`, `seaborn` → visualization  
  - `scikit-learn` → model building & evaluation  

---

## 🔍 Methodology  

1. **Preprocessing**  
   - Train-test split  
   - Feature scaling (for Logistic Regression)  
   - No manual feature selection (Random Forest manages this internally)  

2. **Model Training**  
   - Logistic Regression → Baseline model  
   - Decision Tree → Rule-based learning  
   - Random Forest → Ensemble approach for better generalization  

3. **Performance Evaluation**  
   - Metrics: Accuracy, F1-score  
   - Visuals: Confusion Matrix & Feature Importance plots  

---

## 📊 Model Performance  

| Model               | CV Accuracy | CV F1 | Test Accuracy | Test F1 |
|----------------------|-------------|-------|----------------|---------|
| Logistic Regression  | ~0.84       | ~0.83 | ~0.84          | ~0.83   |
| Decision Tree        | ~0.86       | ~0.85 | ~0.87          | ~0.86   |
| Random Forest        | ~0.88       | ~0.87 | ~0.89          | ~0.88   |

- ✅ **Random Forest achieved the highest accuracy** among all models.  
- **Top contributing features:** sleep quality, blood pressure, safety, and career anxiety.  

---

## 📈 Visual Insights  

- **Confusion Matrix:** Model prediction breakdown.  
- **Feature Importance Graph:** Shows dominant stress factors.  
- **Performance Bar Chart:** Quick comparison between models.  

---

## 🧩 Key Findings  

- ML models can **predict student stress** with accuracy above 85%.  
- **Lifestyle and health-related** aspects have strong correlations with stress.  
- Ensemble techniques like **Random Forest** offer the best reliability and robustness.  

---

## 🚀 Future Enhancements  

- Expand dataset size and diversity.  
- Include **time-based data** to capture stress progression.  
- Develop a **web or mobile app** for real-time stress prediction and monitoring.  

---

## ⚖️ License  

Distributed under the **MIT License**. You may freely use, modify, or redistribute this project.  

---
