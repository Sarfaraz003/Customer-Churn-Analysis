# 📊 Customer Churn Analysis  

## 📌 Project Overview  
Customer retention is a critical challenge for businesses, especially in subscription-based industries like telecom. This project analyzes a **Telco Customer Churn dataset** to identify factors influencing customer churn and builds a predictive model to help businesses reduce churn and improve long-term customer relationships.  

### 🎯 Objective
The goal of this project is to analyze customer churn behavior and build a simple predictive model to identify customers who are at risk of leaving.  
This project is done using **R** with minimal libraries, showcasing clear logic and business-focused insights.  

---

### 🔹 Steps Performed

1. **Data Exploration**
   - Loaded dataset, checked structure, summary, missing values.
   - Found total customers = **7043**, churned customers = **1869** (~**26.54 % churn rate**).

2. **Exploratory Analysis**
   - Customers with **month-to-month contracts** showed higher churn.
   - Customers with **higher monthly charges** tended to churn more.
   - **Tenure** (how long they stayed) strongly influenced churn — new customers are more likely to leave.

3. **Modeling (Logistic Regression)**
   - Built a logistic regression model using tenure, contract type, and monthly charges.
   - Model achieved an accuracy of **78.73%** and AUC of **0.8271**.

4. **Evaluation**
   - Confusion matrix shows the model correctly identified a majority of churn cases.
   - ROC curve confirms good separation between churn vs. non-churn customers.

---

### 📈 Business Insights

- **Churn Rate:** About **26.54%** of customers have churned.  
- **Contract Type:** Month-to-month customers are **25.58 times** more likely to churn compared to long-term contract holders.  
- **Tenure:** Average tenure of churned customers = **38 months**, non-churn = **18 months**.  
- **Charges:** Customers with higher monthly charges (~**₹74.44**) tend to churn more frequently.  

---

### 🚀 Recommendations
- Incentivize customers to move from **month-to-month** to **annual/2-year contracts**.  
- Offer **loyalty benefits** to long-tenure customers (discounts, add-on services).  
- Target **high-charges customers** with value-added services or personalized offers to reduce churn.   



✨ *If you’re a recruiter or professional viewing this project, I’d be glad to discuss how my skills can contribute to your team’s success.*
