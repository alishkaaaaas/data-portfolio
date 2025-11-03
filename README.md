# data-portfolio
# Customer Churn Prediction (Machine Learning Project)

**Author:** Kamza Alisher  
**Goal:** Predict whether a telecom customer will churn based on their contract and usage data.  
**Tools:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  

---

## 📊 Project Overview
This project demonstrates the end-to-end process of building a churn prediction model:
1. Data cleaning and preprocessing  
2. Encoding categorical features  
3. Training a Random Forest Classifier  
4. Evaluating model performance  
5. Interpreting important features  

---

##  Dataset
**Source:** [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)  
**Size:** 7,043 rows, 21 columns  

Each row represents a customer with details about:
- Demographics (gender, senior citizen, dependents)  
- Contract & billing (contract type, payment method, monthly charges)  
- Target: `Churn` (1 = yes, 0 = no)

---

##  Process
```mermaid
graph TD;
A[Import Dataset] --> B[Clean Missing Data];
B --> C[Encode Categorical Features];
C --> D[Train-Test Split];
D --> E[Train Model];
E --> F[Evaluate & Visualize];

