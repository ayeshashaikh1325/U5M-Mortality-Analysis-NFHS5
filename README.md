# 📊 Determinants of Under-Five Child Mortality
### Advanced Regression Analysis using NFHS-5 Data

![Python](https://img.shields.io/badge/R-Statistical%20Analysis-276DC3?style=flat&logo=r)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Data](https://img.shields.io/badge/Data-NFHS--5-blue)

---

## 📌 Overview
This project investigates the key socio-demographic and maternal factors 
affecting under-five child mortality in India using NFHS-5 survey data 
(~6.37 lakh households). Three statistical and ML models were applied 
separately to urban and rural populations to identify policy-relevant 
predictors of child survival.

---

## 🎯 Objectives
- Identify key determinants of under-five mortality across urban and rural populations
- Compare predictive capability of MLR, Random Forest, and Logistic Regression
- Translate findings into actionable public health policy recommendations

---

## 📂 Dataset
- **Source:** National Family Health Survey — NFHS-5 (2019–2021)
- **Coverage:** 29 States + 8 UTs, ~6.37 lakh households
- **Target Variable:** `ChildAlive` (0 = Death, 1 = Survival)
- **Predictors:** Religion, Gender, Birth Order, Child Size at Birth, 
Maternal & Paternal Education, Wealth Index, Place of Delivery

---

## 🔬 Methodology

| Model | Urban | Rural | Best For |
|-------|-------|-------|----------|
| Multiple Linear Regression (MLR) | R² ≈ 1.4% | R² ≈ 1.0% | Trend analysis |
| Random Forest | ~96-97% accuracy | ~96-97% accuracy | Feature importance |
| Logistic Regression | AUC 0.53–0.67 | AUC 0.53–0.67 | Policy inference ✅ |

---

## 📈 Key Findings
- **Child size at birth** — strongest predictor of mortality across all models
- **Maternal education & Wealth Index** — significant socioeconomic predictors
- **Random Forest** achieved high accuracy but failed to classify minority class (death) due to class imbalance
- **Logistic Regression (Model 6)** — recommended as best model for policy-relevant inference

---

## 🏆 Best Model
**Logistic Regression — Full Model (Model 6)**
- Provides interpretable Odds Ratios (OR)
- Stable across urban and rural samples
- Most suitable for imbalanced public health datasets

---

## 💡 Policy Recommendations
1. Prioritize early identification of small-sized infants
2. Invest in maternal education programs
3. Target low-wealth households with focused health interventions
4. Strengthen rural postnatal care infrastructure

---

## 🛠️ Tech Stack
![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

---

## 👥 Contributors
- Ayesha Shaikh
- Krutika Kondagule
- Siddharth Gaikwad
- Faiza Feroz
- Aditi Pratapwar
- Sakshi Khaire

**Supervised by:** Dr. Richa Panchgaur | Vishwakarma University, Pune
