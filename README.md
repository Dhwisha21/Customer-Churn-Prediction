# Customer-Churn-Prediction
This project builds a predictive model to identify customers likely to stop using a service. It includes data cleaning, EDA, model training (Logistic Regression, Random Forest) performance evaluation, and an interactive Power BI dashboard for business insights.

1. Problem Definition
Companies often lose customers due to poor service, high pricing, lack of engagement, and unresolved issues. The cost of acquiring a new customer is much higher than retaining an existing one. Therefore, predicting churn is essential for:
 Increasing customer lifetime value (CLV)
 Reducing acquisition cost (CAC)
 Improving customer experience and loyalty
 Supporting business decision-making with data
This project aims to develop a predictive model that identifies high-risk customers and explains the drivers behind churn.

2. Dataset & Data Processing

The dataset typically includes customer details such as:
Demographics: Gender, Senior Citizen, Partner, Dependents
Account information: Tenure, Contract type, Payment method
Services used: Internet service, security addons, tech support
Billing: Monthly charges, total charges
Target variable: Churn (Yes/No)

Data Cleaning Steps:
Removed missing and inconsistent values
Converted string labels to numerical categories
Scaled numerical features where necessary
Engineered new features to enhance model performance (optional)

Encoding Techniques:
Label Encoding
One-Hot Encoding

3. Exploratory Data Analysis (EDA)
In the notebook, multiple visualizations help understand churn patterns:
Churn distribution plot
Correlation heatmap
Distribution of monthly charges for churned vs non-churned customers
Impact of contract type on churn
Tenure vs churn behavior
Bar charts showing high-risk service categories

Key Insights Found:
Month-to-month contract customers churn the most
Higher monthly bills strongly correlate with churn
Customers without tech support or security services churn more
Customers with lower tenure are more likely to leave
These insights help the business understand where improvements are needed.

4. Machine Learning Models Developed

The following ML models are trained and compared:

Logistic Regression
Simple, interpretable model that gives clear insights into feature importance.

Random Forest
Ensemble model that handles complex patterns and reduces overfitting.

XGBoost
Boosting algorithm known for high accuracy and performance on churn datasets.

Evaluation Metrics:
Accuracy
Precision
Recall
F1-score
Confusion Matrix
ROC & AUC Score
The final model is selected based on the highest recall for churn class because identifying customers who might leave is more important than predicting who will stay.

5. Power BI Dashboard
An interactive Power BI file is included to visualize business insights.
Dashboard Includes:
Churn Overview Page
Customer Demographics Analysis
Subscription & Contract Types
Billing Insights
High-Risk Customer Segments
Users can explore:
Which groups churn the most
What services churned customers commonly subscribe to
Which demographics have the highest retention
Billing patterns causing churn
This helps managers and marketing teams take real retention actions.

6. Project Outcome
The churn prediction system enables businesses to:
Identify customers at high risk of leaving
Take preventive actions (discounts, calls, service improvements)
Understand the most important churn drivers
Optimize customer retention strategy
Increase revenue and loyalty
By combining machine learning with interactive analytics, the project provides both predictive power and business value.

7. Technologies Used
Python
pandas
numpy
scikit-learn
matplotlib
seaborn
xgboost
joblib

Notebook Environment
Jupyter Notebook

Data Visualization
Power BI Desktop


