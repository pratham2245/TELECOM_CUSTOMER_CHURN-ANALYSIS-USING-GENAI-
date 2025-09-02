# TELECOM_CUSTOMER_CHURN-ANALYSIS-USING -GENAI
<img width="800" height="428" alt="image" src="https://github.com/user-attachments/assets/bf866f4a-6058-49b6-83b1-8b5a70b6955a" />

# Objective:
The objective of this project is to analyze customer behavior and identify the key factors influencing customer churn in a telecom company. By leveraging exploratory data analysis (EDA), statistical methods, and machine learning models, the project aims to:

Understand patterns and drivers of churn (e.g., contract type, tenure, payment method, service usage).

Build predictive models to classify customers as likely to churn or stay.

Provide actionable insights and recommendations to improve customer retention, reduce revenue loss, and enhance business decision-making.

# SUMMARY
The dataset consists of 7,043 customers with features such as demographics, services subscribed, contract type, billing, and payment methods.

The target variable is Churn (Yes/No). Around 26–27% of customers are churners, showing a class imbalance.

Key churn drivers identified:

Contract type: Customers on month-to-month contracts churn far more than those on yearly contracts.

Internet service: Fiber optic users have higher churn compared to DSL.

Additional services (Online Security, Tech Support, Device Protection) reduce churn likelihood.

Payment method: Customers using Electronic Check show higher churn compared to automatic payments.

Tenure: Newer customers (low tenure) are more likely to churn.

Machine learning models (likely Logistic Regression, Random Forest, or XGBoost in your notebook):

Achieved around 78–82% accuracy, with a good balance of precision and recall.

Feature importance highlighted Contract, Tenure, InternetService, OnlineSecurity, and PaymentMethod as most influential.
