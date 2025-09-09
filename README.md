# 📱 S-Mobile: Predicting Customer Churn  

This project applies **data science and predictive analytics** to address the critical issue of **customer churn** for *S-Mobile*, a mobile telecommunications provider in Singapore.  

The goal is to **predict which customers are at risk of leaving** and design **data-driven retention strategies** that improve profitability, customer satisfaction, and long-term value.  

---

## 📌 Project Overview  
Customer churn is one of the biggest challenges for telecom companies, since acquiring a new customer is far more costly than retaining an existing one. By leveraging **historical customer data**—including usage patterns, billing history, customer service interactions, and equipment details—this project develops predictive models that flag at-risk customers *before* they leave.  

**Key objectives:**  
1. Analyze customer data to uncover churn patterns and behaviors.  
2. Develop and compare machine learning models for churn prediction.  
3. Identify the most important features driving churn.  
4. Translate findings into **actionable retention strategies**.  
5. Quantify the **economic impact** of these strategies using Customer Lifetime Value (CLV).  

---

## 🔍 Methodology  

### 1. Data Preparation  
- **Data Sources:** Customer account histories, call/SMS/data records, billing information, and support tickets.  
- **Preprocessing:**  
  - Handled missing values  
  - Normalized features  
  - Encoded categorical variables  
- **Feature Engineering:** Created derived metrics such as:  
  - Customer tenure  
  - Usage trends (minutes, revenue, overage, roaming)  
  - Payment and billing patterns  
  - Frequency of service complaints and retention calls  
  - Device-related characteristics (handset type, age, refurbishment status)  

---

### 2. Modeling Approach  
- **Baseline Models:**  
  - Logistic Regression (interpretable baseline)  
  - Decision Trees  
  - Random Forests  
- **Advanced Models:**  
  - Gradient Boosting (XGBoost, LightGBM)  
  - Neural Networks (for complex interactions)  
- **Evaluation Metrics:**  
  - Accuracy  
  - Precision / Recall  
  - F1 Score  
  - ROC-AUC (emphasis on handling class imbalance with representative churn rate ~2%)  

---

### 3. Insights & Actions  
- **Key churn drivers identified:**  
  - High volume of customer care calls  
  - Network quality issues (dropped calls)  
  - Declining usage trends (revenue, minutes)  
  - Long handset tenure (aging devices)  
  - Travel and regional differences  
- **Targeted retention strategies proposed:**  
  - Proactive outreach for customers with frequent service complaints  
  - Device upgrade incentives for customers with old handsets  
  - Usage-based offers (roaming bundles, bonus minutes) for declining users  
  - Personalized campaigns based on customer value and churn probability  

---

### 4. Business & Economic Evaluation  
- Simulated the impact of retention offers on **Customer Lifetime Value (CLV)** across a **5-year horizon**.  
- Conducted breakeven analysis to identify at which cost levels retention strategies become profitable.  
- Showed that **proactive churn management outperforms reactive approaches**, both financially and in customer satisfaction.  

---

## 🛠️ Tools & Libraries  
- **Python**: pandas, numpy, matplotlib, seaborn  
- **scikit-learn**: Logistic Regression, Random Forests, model evaluation  
- **XGBoost / LightGBM**: Boosting models for higher predictive performance  
- **Visualization**: Feature importance plots, partial dependence plots  
- **Jupyter Notebook**: End-to-end interactive analysis and documentation  

---

## 💡 Key Skills & Concepts  
- **Customer Churn Prediction**  
- **Machine Learning & Model Evaluation**  
- **Feature Engineering**  
- **Data Visualization & Interpretability**  
- **Retention Analytics & Strategy**  
- **Customer Lifetime Value (CLV) modeling**  
- **Business-Driven Data Science**  

---

## 🚀 Key Takeaways  
- Predictive analytics allows **telecom providers to act before customers churn**, reducing dependency on reactive “save desk” strategies.  
- **Interpretability tools** (Permutation Importance, Partial Dependence Plots) bridge the gap between machine learning outputs and business strategy.  
- Data-driven targeting enables **cost-effective retention campaigns** that maximize ROI.  
- A combination of **machine learning + business strategy** delivers the best results: accurate churn prediction, actionable insights, and measurable impact on profitability.  

---
