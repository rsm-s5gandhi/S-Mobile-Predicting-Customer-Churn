# 📱 S-Mobile: Predicting Customer Churn  

## 📌 Project Overview  
This project is based on the *Kellogg School of Management case study “S-Mobile: Predicting Customer Churn” (2025)*.  
The challenge was to help **S-Mobile**, a leading telecom provider in Singapore, proactively identify at-risk customers and reduce churn using predictive analytics.  

**Objectives:**  
1. Build a model to predict customer churn.  
2. Understand the main drivers of churn.  
3. Design targeted offers and incentives.  
4. Quantify the business impact of retention strategies.  

---

## 🗂 Data Preparation  
- Collected datasets with **training (27,300), test (11,700), and representative (30,000)** customers.  
- Adjusted churn rates in the representative dataset (**2%**) using **case weights**.  
- Cleaned and pre-processed variables across categories:  
  - *Customer Usage*: revenue, minutes of use, overage, roaming calls.  
  - *Customer Actions*: calls to customer care, retention team.  
  - *Quality Metrics*: dropped calls.  
  - *Equipment*: handset age, smartphone vs refurbished devices.  
  - *Demographics*: credit rating, occupation, region, travel.  

---

## ⚙️ Methodology  
1. **Exploratory Data Analysis (EDA):** visualized distributions, correlations, churn patterns.  
2. **Baseline Model:** Logistic Regression (required by the case).  
3. **Advanced Models:** Random Forest, Gradient Boosting to capture non-linear effects.  
4. **Interpretability:** Identified top churn drivers using:  
   - Permutation Importance  
   - Partial Dependence Plots  
5. **Business Recommendations:** Designed actions tailored to churn drivers.  
6. **Economic Evaluation:** Modeled **Customer Lifetime Value (CLV)** impact over 5 years.  

---

## 🤖 Modeling Approach  
- **Logistic Regression:** baseline interpretable model.  
- **Tree-based Models:** captured interactions and non-linearities.  
- **Evaluation Metrics:** Accuracy, ROC-AUC, Precision, Recall, and Calibration.  
- **Prediction Scaling:** Adjusted outputs for the representative sample (**2% churn**).  

---

## 🛠 Tools & Libraries  
- **Python:** pandas, numpy, scikit-learn, matplotlib, seaborn  
- **ML Models:** Logistic Regression, Random Forest, Gradient Boosting  
- **Model Explainability:** Permutation Importance, Partial Dependence Plots  
- **Business Analytics:** CLV calculations, cost-benefit analysis  

---

## 🎯 Key Skills & Concepts Demonstrated  
- **Machine Learning:** classification models, feature importance, model evaluation.  
- **Data Science Workflow:** data cleaning, preprocessing, EDA, model building.  
- **Interpretability:** turning model outputs into business insights.  
- **Business Strategy:** translating analytics into customer retention initiatives.  
- **Economics & CLV:** quantifying long-term value of retention actions.  

---

## 🚀 Key Findings  
- **Top churn drivers:** high customer care calls, dropped voice calls, declining usage, handset age, international travel.  
- **Proposed targeted actions:** proactive outreach, device upgrades, usage incentives, personalized offers.  
- Retention strategies showed potential to **reduce churn while improving ROI**.  

---
