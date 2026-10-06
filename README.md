# Telecom_Customer_Churn_Analysis
Telecom Customer Churn Analysis &amp; EDA A data analysis and exploratory data analysis (EDA) project focused on analyzing customer churn patterns within a telecommunications dataset. This repository provides data cleaning workflows, statistical summaries, and categorical distribution visualizations to identify key drivers behind customer churn.
🛠️ What I Did in This ProjectCleaned the Data: 
Fixed missing values and updated formatting, like changing blank entries in TotalCharges to 0 and converting the SeniorCitizen column into clear "Yes" or "No" labels.   
Looked for Patterns: Checked all 7,043 customers across 21 columns to see who left the company and who stayed.
Compared Features: Looked at how factors like contract length, internet type, and extra features affected whether a customer canceled.   
Calculated Key Numbers: Worked out average monthly payments, total costs, and customer time with the company.

💡 Simple Insights FoundContract Type Matters: 
People on Month-to-Month plans leave much more often than people on 1-year or 2-year plans.   
New Customers Leave First: Most customers who cancel leave within their first year.   
Fiber Optic Issues: Customers with Fiber Optic internet leave more often than DSL users, likely because it costs more.   
Extra Features Help Keep Customers: People who use extra services like Online Security or Tech Support are much less likely to leave.   
High Monthly Bills: High monthly prices without any discounts lead to more cancellations. 

🏢 Why This Is Useful for Business
Spots At-Risk Customers: Helps the company figure out who is about to cancel before they actually leave.   
Saves Marketing Money: Allows the business to focus special offers only on the customers who need them.   
Shows What Services Work Best: Reveals which features keep customers happy and loyal long-term.   
Protects Income: Helps the company keep more customers, which keeps money coming in.   

🔄 Changes the Business Should MakePush Yearly Plans: 
Offer small discounts to get Month-to-Month customers to sign 1-year or 2-year deals.   
Help New Customers Early: Pay extra attention to new customers during their first 90 days so they don't leave early.   
Bundle Security Features: Include free or low-cost Online Security and Tech Support in basic plans so customers stay longer.   
Fix Fiber Optic Issues: Check if Fiber Optic prices are too high or if the service has technical problems.   
Send Automatic Alerts: Set up automatic warnings when a customer's bill gets high so the team can reach out with a better offer.

📌 Project Overview & Technical Execution
Data Wrangling & Cleaning: Standardized raw customer data by casting TotalCharges to float, replacing whitespace entries with zeroes, and converting SeniorCitizen numeric codes into explicit categorical labels (yes/no).   
Exploratory Data Analysis (EDA): Analyzed 7,043 customer records across 21 variables to evaluate distributions for tenure, MonthlyCharges, and service adoption.   
Feature Relationship Mapping: Evaluated cross-tabulations between categorical predictors (contract types, internet service types, add-on services) and customer churn status.   
Statistical Summarization: Calculated descriptive statistics (mean, median, standard deviation, quartiles) across key continuous metrics to identify central tendencies and variance.  

💡 Key Analytical Insights Found
Contract Duration Impact: Customers on Month-to-Month contracts exhibit significantly higher churn rates compared to those on 1-year or 2-year commitments.   
Tenure Vulnerability Window: Highest attrition occurs within the first 1–12 months of customer onboarding, after which retention rates stabilize significantly.   
Internet Service Disparity: Fiber optic subscribers show a higher rate of churn compared to DSL users, likely driven by higher pricing or service expectation mismatches.   
Add-On Protection Effect: Customers without value-added security services (Online Security, Tech Support, Device Protection) are substantially more likely to churn.   
Pricing Thresholds: High MonthlyCharges without attached contract discounts correlate strongly with account cancellations. 

🛠️ Tech Stack & DependenciesThe notebook uses standard Python data science libraries:   
Python 3.xPandas: Data manipulation, cleaning, and tabular data analysis   
NumPy: Numerical computations and array operations   
Matplotlib: Core visual graphing library   
Seaborn: Statistical and visual data plotting   

📊 Dataset OverviewSource File: 
Customer Churn.csv   
Size: 7,043 rows and 21 columns   
Target Variable: Churn (Yes / No)   



