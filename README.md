BCG Data Science & Analytics Virtual Internship – Project README
🚀 About the Project

This project was completed as part of the BCG Data Science & Analytics Virtual Internship Programme (Forage).

The client, PowerCo, is a major gas and electricity utility company serving corporate, SME, and residential customers across Europe. Due to energy market liberalization, the company has experienced significant churn, especially within the SME segment.

The objective of this project was to test the hypothesis that customer churn is primarily driven by price sensitivity. The analysis included Exploratory Data Analysis (EDA), hypothesis testing, feature engineering, predictive modeling, and business-focused recommendations regarding a proposed 20% discount strategy.

📌 Project Requirements

Frame churn prediction as a classification problem.

Perform exploratory data analysis to understand churn behavior.

Define and test price sensitivity as a potential churn driver.

Engineer features and build a Random Forest classifier.

Evaluate model performance and connect results to business impact.

🛠 Tools & Technologies

💻 Google Colab

🐍 Python

📊 Pandas & NumPy

📈 Matplotlib & Seaborn

🤖 Scikit-learn

📁 CSV datasets (customer, pricing, churn data)

⚠️ Challenges Faced

Data Cleaning & Preprocessing – Handling missing values, encoding categorical variables, and merging multiple datasets correctly.

Defining Price Sensitivity – Converting a business assumption into measurable features using pricing and consumption variables.

Class Imbalance – Churn rate (~9–10%) created imbalance, requiring careful selection of evaluation metrics.

Business Interpretation – Translating model performance (precision, recall, F1-score) into financial impact and discount strategy decisions.

🔍 Key Insights

Customer churn rate was approximately 9–10%, which is financially significant for the SME segment.

Price was not the strongest driver of churn. Consumption over the last 12 months, forecasted meter rent, and net margin had stronger relationships with churn.

Customers who stayed beyond the first five months showed a significantly lower probability of churning.

Gas subscription status and electricity consumption patterns influenced churn more than pricing changes alone.

💡 Recommendations

Focus on retaining customers during the first five months through better onboarding and engagement strategies.

Avoid automatically offering a 20% discount, as price is not the main churn driver and blanket discounts may reduce revenue unnecessarily.

🤖 Deploy the Random Forest model to identify high-risk customers before applying incentives.

📊 Implement a targeted discount strategy based on predicted churn probability and customer margin instead of a flat discount policy.
