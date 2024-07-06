# BCG_jobSimulation_dataScience
BCG_jobSimulation_dataScience_PowerCo
******************************************************
# Client Data Analysis and Churn Prediction Project

## Overview
This project aims to address client data analysis and churn prediction for Powerco, focusing on identifying key trends and building a predictive model to mitigate customer attrition. The tasks are divided into four main areas: data analysis, data visualization, feature engineering, and predictive modeling.

## Task 1: Determining Client Data and Approach

### Client Data Needed for Analysis
To perform a thorough analysis, the following client data is required:
- Customer demographics (age, gender, location)
- Subscription details (plan type, contract duration, start and end dates)
- Usage data (monthly power consumption, peak usage times)
- Billing information (monthly bills, outstanding amounts, payment methods)
- Customer service interactions (complaints, support tickets, resolution times)
- Churn indicators (cancellation requests, feedback forms)

### Techniques for Investigating Client's Problem
To investigate the client's problem, the following techniques will be employed:
1. **Data Cleaning:** Remove duplicates, handle missing values, and standardize data formats.
2. **Exploratory Data Analysis (EDA):** Use statistical methods and visualizations to uncover patterns and insights.
3. **Feature Engineering:** Create new variables that capture important aspects of the data, such as average monthly consumption and customer tenure.
4. **Predictive Modeling:** Apply machine learning techniques, specifically a Random Forest Classifier, to predict customer churn.

### Email to Associate Director
Subject: Approach for Client Data Analysis and Churn Prediction

Dear [Associate Director’s Name],

I hope this email finds you well. I am writing to summarize my approach for analyzing the client data and addressing their churn prediction concerns.

To thoroughly investigate the client's problem, I will be focusing on the following key areas:
- **Data Collection:** Gathering comprehensive client data, including demographics, subscription details, usage data, billing information, customer service interactions, and churn indicators.
- **Data Cleaning and Preparation:** Ensuring data quality by removing duplicates, handling missing values, and standardizing formats.
- **Exploratory Data Analysis:** Utilizing statistical methods and visualizations to uncover patterns and insights.
- **Feature Engineering:** Creating new variables that capture essential aspects of the data for better model performance.
- **Predictive Modeling:** Employing a Random Forest Classifier to accurately predict customer churn and provide actionable insights.

I will keep you updated on the progress and findings as the project advances. Please let me know if you have any questions or require further details.

Best regards,
[Your Name]

## Task 2: Data Analysis and Visualization

### Python Data Analysis
Using Python, I analyzed the client data to identify key trends and insights. The analysis involved:
- Cleaning the data to ensure accuracy and consistency.
- Performing EDA to explore the data distribution, relationships, and patterns.
- Creating visualizations to interpret key trends effectively.

### Data Visualizations
To aid in interpreting key trends, I created various visualizations, including:
- **Histograms and Box Plots:** To understand the distribution of continuous variables such as monthly consumption and billing amounts.
- **Bar Charts:** To compare categorical variables like plan types and customer demographics.
- **Heatmaps:** To visualize correlations between different features.

## Task 3: Feature Engineering

### New Feature Creation
Using Python, I built new features to enhance the analysis. Some of the key features include:
- **Average Monthly Consumption:** Calculated from the usage data.
- **Customer Tenure:** The duration of the customer’s subscription.
- **Time Since Last Contract Update:** The time elapsed since the last update to the customer's contract.

These features were incorporated into the predictive model to improve its accuracy and reliability.

## Task 4: Predictive Modeling

### Building a Predictive Model for Churn
To address customer attrition, I built a predictive model using the Random Forest technique. The model's objective was to predict the probability of customer churn and identify high-risk customers.

#### Executive Summary
**Context:**
Powerco is grappling with customer attrition, attributed to customers being sensitive to pricing. To address this issue, they are considering a strategy of offering a 20% discount to customers at a higher risk of leaving.

**Machine Learning Approach:**
Following data cleaning, exploratory data analysis (EDA), and feature engineering, I employed a Random Forest Classifier. The model successfully predicts the probability of customer churn, achieving an accuracy rate of 90% and a precision score of 91% on the test dataset.

**Key Findings:**
- Approximately 9.7% of customers have churned, while the remaining 90% have not.
- The net margin on power subscription and consumption over a 12-month period emerges as a significant factor influencing churn.
- The forecasted bill for meter rental in the next two months also plays a pivotal role in customer attrition.
- Temporal factors, such as the duration of customer activity, tenure, and the time since the last contract update, are notably influential in predicting churn.

## Conclusion
This project has provided valuable insights into customer behavior and churn prediction for Powerco. By leveraging data analysis, feature engineering, and predictive modeling, we can effectively identify high-risk customers and implement targeted strategies to reduce attrition. The findings and techniques outlined in this project will be instrumental in enhancing Powerco's customer retention efforts.
