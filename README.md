Customer Churn Prediction using Random Forest
📌 Overview

This project analyzes customer churn in a subscription-based business and applies a Random Forest classifier to predict customers who are likely to churn. The goal is to identify key churn drivers and translate model outputs into actionable business recommendations.

🎯 Objectives

Explore customer behavior using EDA

Identify key factors influencing churn

Build and evaluate a Random Forest churn prediction model

Provide data-driven business insights

📊 Key EDA Insights

Churn is highest among new customers (0–11 months tenure).

Month-to-month contracts show significantly higher churn than long-term contracts.

Customers without support and security services churn more.

Fiber optic internet users exhibit higher churn.

Demographic features such as gender have minimal impact.

🌲 Random Forest Model

Random Forest was chosen for its ability to capture non-linear relationships and feature interactions.

Model performance was evaluated using confusion matrix, precision, recall, F1-score, and ROC-AUC.

The model performed well on customers with clear behavioral churn signals but struggled with sudden or externally driven churn.

💡 Business Recommendations

Prioritise high-risk, high-value customers for retention.

Improve onboarding and early engagement strategies.

Encourage long-term contracts and value-added services.

Use targeted incentives for month-to-month customers.

🛠️ Tech Stack

Python

Pandas, NumPy

Matplotlib

Scikit-learn

Seaborn

🚀 Conclusion

The Random Forest model effectively identifies churn risk using behavioral and contractual features, enabling proactive customer retention strategies.
