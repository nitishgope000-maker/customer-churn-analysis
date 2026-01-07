📊 Customer Churn Analysis – Python Project

Author: Nitish Gope
Tools Used: Python · Pandas · NumPy · Matplotlib · Seaborn
Dataset: Telco Customer Churn (7,043 records)

🔍 Project Overview

This project analyzes customer churn for a telecom company using Python.
The goal is to identify:

Which customers are most likely to churn

What factors influence churn

How to improve customer retention

The analysis includes data cleaning, feature engineering, exploratory data analysis (EDA), visualization, and final insights with business recommendations.

🧹 1. Data Cleaning & Preparation

Steps performed:

Loaded dataset into a Pandas DataFrame

Converted TotalCharges from object → float

Removed missing values

Removed duplicate rows

Standardized datatypes

Prepared dataset for analysis

🛠️ 2. Feature Engineering

Created additional features to improve segmentation:

🔹 ContractBucket

Groups contract types:

Short-Term (Month-to-month)

Mid-Term (One year)

Long-Term (Two year)

🔹 TenureBand

Created tenure ranges:

0–3 months

3–12 months

12–24 months

24–48 months

48–72 months

These engineered columns helped reveal important churn patterns.

📈 3. Exploratory Data Analysis (EDA)

Generated 11 visualizations including:

Countplot of Churn

Churn by Gender

Churn by Senior Citizen

MonthlyCharges distribution

Tenure distribution

Churn by Contract Type

Churn by Contract Bucket

Churn by Tenure Band

Boxplots for MonthlyCharges and Tenure vs Churn

Correlation heatmap

Visualizations helped identify high-risk segments and churn trends.

⭐ 4. Key Insights

✔ 1. Contract type is the strongest churn factor

Month-to-month customers churn significantly more than yearly or two-year customers.

✔ 2. Early-tenure customers churn the most

Customers with 0–3 months tenure have the highest churn rate.

✔ 3. High monthly charges correlate with churn

Customers paying higher MonthlyCharges tend to leave more often.

✔ 4. Final important insight (as per analysis)

Around 32% of churned customers were:

On month-to-month contracts

With 0–3 months tenure

Indicating onboarding issues or dissatisfaction in the early stage.

🎯 5. Recommendations

Based on insights:

Improve onboarding experience for new customers

Offer early tenure incentives, discounts, or engagement campaigns

Encourage upgrades from monthly → yearly contracts

Review pricing for high-charge customer segments

Provide personalized retention offers using customer segmentation

📁 Files in This Repository
├── Customer_Churn_Analysis_Nitish.ipynb
├── Telco_Customer_Churn.csv
└── README.md

🚀 How to Run the Project
1. Install required libraries
pip install pandas numpy matplotlib seaborn

2. Open the Jupyter Notebook

Use:

Jupyter Notebook

Google Colab

VS Code

3. Run all cells sequentially

All steps are labeled clearly.

🧑‍💻 About the Author

Nitish Gope
Aspiring Data Analyst
Skilled in SQL, Python, Excel, Power BI
Passionate about data insights and dashboard design.
