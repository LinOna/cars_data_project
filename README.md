# cars_data_project
Vehicle Pricing & Fuel Efficiency Analysis
This project explores relationships between vehicle characteristics, pricing, and fuel efficiency, using a dataset of cars with attributes such as MSRP, horsepower, drivetrain, transmission type, and MPG. The analysis focuses on uncovering pricing patterns, performance trade-offs, and market trends, while applying rigorous data cleaning, imputation, and feature engineering strategies to ensure high-quality results.

🔍 Project Objectives
Identify how vehicle size, drivetrain, and horsepower influence MSRP.
Explore the trade-off between performance (HP) and efficiency (MPG).
Assess the impact of transmission types on city vs. highway fuel economy.
Apply data cleaning and imputation to handle missing values while preserving dataset integrity.
Engineer new features (e.g., Price per HP, Total MPG, Vehicle Age) to enrich analysis and highlight market insights.

🛠️ Methods & Workflow
Data Cleaning & Imputation
Hierarchical imputation of missing horsepower and cylinders.
Random Forest classification to impute missing market categories.
Consistency checks and minimal row removal for incomplete fields (e.g., Number of Doors).
Exploratory Data Analysis (EDA)
Correlation analysis of MSRP, horsepower, and MPG.
Visualizations of price distributions across vehicle sizes and drivetrains.
Detection of outliers (e.g., exotic cars with 12–16 cylinders).
Feature Engineering
Price per Horsepower as a measure of value.
Total MPG as an efficiency summary metric.
Vehicle Age for lifecycle and depreciation insights.

📈 Key Findings
Larger vehicles and AWD/RWD drivetrains generally command higher prices, reflecting performance and prestige positioning.
Horsepower strongly correlates with MSRP (r ≈ +0.78), confirming performance as a key pricing driver.
Transmission design impacts efficiency: most have higher highway MPG, while direct drive shows atypical city > highway MPG.
Performance vs. efficiency trade-off: higher horsepower correlates with lower MPG; luxury vehicles tend to sacrifice efficiency.

