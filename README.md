BCG Data Science & Analytics Virtual Internship – Project README
About the Project

This project was completed as part of the BCG Data Science & Analytics Virtual Internship Programme (Forage).

The client, PowerCo, is a major gas and electricity utility company serving corporate, SME, and residential customers across Europe. Due to energy market liberalization, the company has experienced significant churn, particularly within the SME segment.

BCG was engaged to investigate the drivers of churn and test the hypothesis that customer price sensitivity is the primary reason for churn. The project involved exploratory data analysis, hypothesis testing, feature engineering, predictive modeling, and strategic business recommendations regarding a proposed 20% discount strategy.

Project Requirements

Formulate churn as a data science classification problem and test the hypothesis that price sensitivity drives churn.

Perform exploratory data analysis (EDA) to understand customer behavior and identify churn indicators.

Engineer predictive features and build a Random Forest classifier to predict churn probability.

Evaluate model performance and connect predictions to business impact, particularly regarding discount strategies.

Tools & Technologies

Google Colab for model development and experimentation.

Python for data analysis and machine learning.

Pandas & NumPy for data manipulation and numerical computations.

Matplotlib & Seaborn for data visualization.

Scikit-learn for feature engineering, model training, and evaluation.

CSV datasets for historical customer, pricing, and churn data.

Challenges Faced

Data Cleaning & Preprocessing – Handling missing values, inconsistent formats, categorical encoding, and ensuring proper merging of customer and pricing datasets.

Defining Price Sensitivity – Translating a business hypothesis into a measurable variable required creating proxy features from available pricing and consumption data.

Class Imbalance – The churn rate (~9–10%) created an imbalanced classification problem requiring careful metric selection.

Model Evaluation & Business Alignment – Connecting technical metrics such as precision and recall to real financial outcomes and discount decisions.

Key Insights

Customer churn rate was approximately 9–10%, indicating moderate but financially significant attrition within the SME segment.

Price was not the strongest driver of churn; consumption over the last 12 months, forecasted meter rent, and net margin showed stronger relationships with churn behavior.

Customers who stayed beyond the first five months showed significantly lower churn probability, highlighting a critical early-retention window.

Gas subscription status and electricity consumption patterns played a more influential role than pricing fluctuations alone.

Recommendations

Focus on retaining customers during the first five months through onboarding engagement strategies rather than blanket discounting.

Avoid automatically applying a 20% discount, as price sensitivity alone does not sufficiently explain churn and may lead to unnecessary revenue loss.

Deploy the Random Forest model to identify high-risk customers, but tie predictions to margin impact before offering incentives.

Implement a targeted discount strategy optimized per customer based on predicted churn probability and expected revenue contribution rather than a flat discount policy.
