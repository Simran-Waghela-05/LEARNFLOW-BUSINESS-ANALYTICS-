## Task 4: Churn Prediction and Prevention
# Problem Statement:
Predict customer churn using this telecom dataset. Identify key factors contributing to
churn and propose retention strategies based on the analysis.

# Steps:
1. Data Understanding: Understanding the dataset and its features.
2. Data Preprocessing: Cleaning and preparing the data for modeling.
3. Exploratory Data Analysis (EDA): Exploring the data to identify patterns and insights.
4. Feature Engineering: Creating new features if necessary.
5. Model Building: Training and evaluating a machine learning model.
6. Model Interpretation: Understanding the key factors contributing to churn.
7. Retention Strategies: Proposing strategies based on the analysis.

# Model Selected: Random Forest Classifier
Random Forest Classifier is a popular choice for churn prediction due to its ability to handle complex relationships in data, provide feature importance rankings, and resist overfitting. 
It performs well with imbalanced datasets (common in churn problems), works with both categorical and numerical features, and often yields good results without extensive tuning. 
Its ensemble nature allows it to capture non-linear patterns and interactions between variables effectively.

# Insights: 
1. Top 10 factors contributing to churn:
      feature                 importance
Total Charges                 0.321646
Total_Charges                 0.257804
Total Revenue                 0.144196
Tenure in Months              0.072185
Total Long Distance Charges   0.038104
Monthly Charge                0.035972
Streaming TV                  0.020254
Streaming Movies              0.018768
Device Protection Plan        0.018064
Online Backup                 0.017131
2. Number of high-risk customers: 2098

# Proposed retention strategies:
1. Offer personalized discounts to high-risk customers.
2. Improve customer support for customers with longer tenure.
3. Introduce loyalty programs to reward long-term customers.
4. Provide additional services or upgrades at reduced prices.
5. Conduct satisfaction surveys and address pain points.


