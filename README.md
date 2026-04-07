# Energy-Churn-Prediction-BCGx---Forage-
Analyzing price sensitivity and predicting customer churn for SME clients using Random Forest.

This README is designed to showcase your technical analytical skills and the business value of your work. It frames the project as a professional consultancy engagement, which is exactly what recruiters look for.

Customer Churn Analysis: BCG X Virtual Internship
Project Overview
-----------------
This project was completed as part of the BCG X Data Analytics Virtual Internship. The goal was to assist a major energy supplier (PowerCo) in understanding why their SME (Small and Medium Enterprise) customers were churning (leaving for competitors).

The analysis focuses on Price Sensitivity—testing the hypothesis that customers are leaving specifically because of price changes—and building a predictive model to identify high-risk customers.

Key Business Questions
-----------------------
Hypothesis Testing: Is churn driven by price sensitivity?

Predictive Modeling: Can we predict which customers will churn next month?

Strategic Impact: Would a 20% discount effectively retain customers at risk?

Technical Stack
----------------
Language: Python

Libraries: Pandas (Data Manipulation), Matplotlib/Seaborn (Visualization), Scikit-learn (Machine Learning).

Model: Random Forest Classifier.

Project Workflow
-----------------
1. Exploratory Data Analysis (EDA)
Churn Distribution: Analyzed the baseline churn rate (approx. 10%) to understand class imbalance.

Price Analysis: Visualized electricity and gas consumption patterns over the last 12 months.

Sales Channels: Identified which acquisition channels resulted in the most loyal vs. most volatile customers.

2. Feature Engineering
Price Differentials: Created features to measure the difference between off-peak prices in December and January to capture "price shocks."

Tenure: Calculated the length of time a customer has been with PowerCo.

Consumption Categories: Segmented customers by usage volume.

3. Predictive Modeling
I utilized a Random Forest Classifier due to its ability to handle non-linear relationships and provide feature importance scores.

Data Splitting: 75% Training / 25% Testing.

Evaluation Metrics: Focused on Recall and Precision rather than just Accuracy, given that the "Churn" class is imbalanced.

Key Insights
-------------
Price Sensitivity is not the main driver: The analysis showed that price changes alone had a weak correlation with churn.

Tenure Matters: New customers are significantly more likely to churn than those who have stayed for more than 3 years.

Predictive Power: The model successfully identified high-risk segments based on consumption "spread" and contract duration.

Recommendations
Targeted Retention: Instead of a blanket discount, PowerCo should offer loyalty rewards to customers entering their 2nd year of service.

Engagement: High-usage customers with erratic consumption patterns should be prioritized for direct account management.

How to Run
-----------
Clone this repository.

Ensure you have the client_data.csv and price_data.csv files in the root folder.

Install dependencies: pip install pandas seaborn matplotlib scikit-learn

Run the Jupyter Notebook: BCG_X.ipynb
