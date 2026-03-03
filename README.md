# BCG Data Science & Analytics Virtual Internship – Churn Analysis Project

---

## 1. About the Project

This project was completed as part of the **BCG Data Science & Analytics Virtual Internship Programme (Forage)**.

The client, **PowerCo**, is a major gas and electricity utility company serving corporate, SME, and residential customers across Europe. Due to energy market liberalization, the company has experienced significant churn, particularly within the SME segment.

The primary objective of this project was to test the hypothesis that customer churn is primarily driven by price sensitivity.

The project included:

1. Exploratory Data Analysis (EDA)  
2. Hypothesis testing  
3. Feature engineering  
4. Predictive modeling  
5. Business-focused recommendations regarding a proposed 20% discount strategy  

---

## 2. Project Requirements

1. Frame churn prediction as a classification problem.  
2. Perform exploratory data analysis to understand churn behavior.  
3. Define and test price sensitivity as a potential churn driver.  
4. Engineer relevant features and build a Random Forest classifier.  
5. Evaluate model performance and connect results to business impact.  

---

## 3. Tools and Technologies Used

1. Google Colab  
2. Python  
3. Pandas  
4. NumPy  
5. Matplotlib  
6. Seaborn  
7. Scikit-learn  
8. CSV datasets (customer, pricing, and churn data)  

---

## 4. Challenges Faced

1. **Data Cleaning and Preprocessing**  
   Handling missing values, encoding categorical variables, and merging multiple datasets accurately.

2. **Defining Price Sensitivity**  
   Translating a business hypothesis into measurable features using pricing and consumption variables.

3. **Class Imbalance**  
   The churn rate (approximately 9–10%) created imbalance in the dataset, requiring careful selection of evaluation metrics.

4. **Business Interpretation**  
   Converting model performance metrics (precision, recall, F1-score) into actionable financial insights and discount strategy decisions.

---

## 5. Key Insights

1. The customer churn rate was approximately 9–10%, which is financially significant within the SME segment.  
2. Price was not the strongest driver of churn. Consumption over the last 12 months, forecasted meter rent, and net margin showed stronger relationships with churn.  
3. Customers who remained beyond the first five months demonstrated a significantly lower probability of churning.  
4. Gas subscription status and electricity consumption patterns influenced churn more than pricing adjustments alone.  

---

## 6. Recommendations

1. Focus on retaining customers during the first five months through improved onboarding and engagement strategies.  
2. Avoid automatically offering a 20% discount, as price is not the primary churn driver and blanket discounts may unnecessarily reduce revenue.  
3. Deploy the Random Forest model to proactively identify high-risk customers before offering incentives.  
4. Implement a targeted discount strategy based on predicted churn probability and customer margin rather than applying a flat discount policy.  
