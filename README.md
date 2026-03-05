# Subscription Churn Prediction

## Overview

Customer churn is one of the biggest challenges for subscription-based businesses. 
When customers cancel their subscriptions, companies lose recurring revenue.

This project builds a machine learning model to predict which customers are most 
likely to churn so that businesses can proactively target them with retention strategies.

The goal is to use data-driven insights to improve customer retention and maximize revenue.

---

## Dataset

The dataset used in this project contains customer subscription data including:

- Customer tenure
- Contract type
- Payment method
- Monthly charges
- Service usage
- Churn status

Target variable:
Churn (whether the customer canceled their subscription)

---

## Tools & Technologies

Python  
Pandas  
NumPy  
Scikit-learn  
Matplotlib  
Seaborn  
Jupyter Notebook  

Machine Learning Models:
- Logistic Regression
- Random Forest

Evaluation Metric:
- ROC-AUC

---

## Project Workflow

1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature engineering
4. Model training
5. Model evaluation
6. Business insights and recommendations

---

## Key Insights

Several important patterns emerged from the analysis:

• Customers on month-to-month contracts churn significantly more often.

• Customers with shorter tenure are more likely to cancel their subscriptions.

• Higher monthly charges correlate with increased churn risk.

These patterns indicate that contract flexibility and early-stage engagement play major roles in customer retention.

---

## Model Performance

Two machine learning models were trained and evaluated:

Logistic Regression  
Random Forest

Random Forest produced the strongest performance with the highest ROC-AUC score, indicating strong predictive ability for identifying customers at risk of churn.

---

## Business Recommendations

Based on the analysis, companies could reduce churn by implementing the following strategies:

1. Encourage customers to switch from month-to-month to yearly contracts.
2. Target new customers with onboarding and engagement campaigns.
3. Offer retention incentives to high-risk customers.
4. Use churn prediction models to trigger automated retention workflows.

---

## Estimated Business Impact

If the company successfully retains even 20% of predicted churn users, 
the model could save tens of thousands of dollars in annual revenue.

Predictive churn modeling allows businesses to shift from reactive to proactive retention strategies.

---

## Future Improvements

Possible improvements for this project include:

- Implementing Gradient Boosting models (XGBoost or LightGBM)
- Building a real-time prediction pipeline
- Incorporating behavioral engagement data
- Creating an automated retention recommendation system

---

## Project Structure

subscription-churn-prediction/

data/  
Dataset files  

notebooks/  
churn_analysis.ipynb  

src/  
preprocessing.py  
modeling.py  

README.md  
requirements.txt

---

## Author

Jonatan Tepale