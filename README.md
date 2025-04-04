# 📦 AutonomousShipment & Customer Analysis Project

This repository includes two business analytics projects combining multi-criteria decision-making, optimisation, and customer segmentation using statistical and machine learning techniques.

---

## 📝 Reports
- [AutonomousShipment Business Analysis Report (PDF)](./AutonomousShipment%20business%20analysis%20report.pdf)

---

## 🚀 Project 1: Autonomous Robot Selection & Optimisation  
**Objective:** Select the best autonomous robot prototype for parcel delivery and determine optimal allocation across store types under business constraints.

### 🔍 Methods & Techniques:
- **TOPSIS (MCDA):** To rank 4 robot prototypes using 5 weighted criteria  
- **Goal Programming:** To optimise robot allocation under constraints (budget, staff hours, minimum units per store)
- **Tools Used:** R (`goalp` package), Excel (normalisation & ranking)

### 🧠 Key Outcomes:
- Selected “Deviant” robot as the optimal prototype (TOPSIS score = 0.609)
- Optimal allocation: 19 robots (Grocery), 5 (Clothing), 5 (Sports Equipment)
- Max achievable orders per day: **221 orders**

---

## 🍷 Project 2: Customer Spending Behaviour Analysis (Drinks@Home.uk)
**Objective:** Identify key factors affecting customer revenue and evaluate campaign strategies.

### 🔍 Methods & Techniques:
- **Linear Regression (in R)**: Predict customer revenue from demographics & behaviour
- **Data Cleaning & Dummification**: Transformed categorical features (ad channels, voucher usage)
- **Exploratory Analysis**: Correlation matrices, assumption checks, model diagnostics

### 📈 Key Insights:
- Positive revenue drivers: **Voucher usage, Income, Influencer advertising**
- Negative drivers: Age, Time on website
- Best next action: **Invest more in Influencer marketing**
- R² ≈ **0.55** — model explains 55% of revenue variation

---

## 📦 Tools Used:
- R, ggplot2, dplyr, goalp, corrgram
- Excel (TOPSIS & MCDA matrix processing)
- CRISP-DM framework

---

## 👤 Author
**Surapot Nonpassopon**  
MSc Data Science and Analytics, University of Leeds  
[GitHub Portfolio](https://github.com/surapotsrp)
