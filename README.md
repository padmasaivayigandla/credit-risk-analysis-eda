Credit Risk Analysis using Exploratory Data Analysis (EDA)
==========================================================
Project Overview
In the consumer finance industry, lending decisions involve significant risk, especially when applicants have limited or no credit history.  
This project uses Exploratory Data Analysis (EDA) to identify patterns and key factors that influence loan default, helping financial institutions make better lending decisions.

The objective is to understand how customer attributes and loan characteristics differ between defaulters and non-defaulters, and to extract actionable business insights that can reduce financial risk.

Business Problem
Loan-providing companies face two major risks:
- Rejecting applicants who are capable of repaying loans (loss of business)
- Approving loans for applicants likely to default (financial loss)

Using EDA, this project aims to:
- Identify drivers of loan default
- Support better risk assessment and decision-making
- Ensure creditworthy customers are not unfairly rejected

Datasets Used
=============
The analysis is based on the following datasets:
- application_data.csv – Customer details and current loan application information
- previous_application.csv – Historical loan application outcomes
- columns_description.csv – Data dictionary describing each variable

Dataset Availability
Due to distribution restrictions and file size limitations, the datasets are not included in this repository.

Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

Analysis Approach
=================
The project follows a structured EDA workflow:

1. Data Understanding
   - Dataset structure, variable types, and target variable analysis
2. Missing Value Analysis
   - Dropping high-missing columns
   - Imputing remaining values using business-driven logic
3. Outlier Analysis
   - Identifying extreme values without removal
4. Target Variable Imbalance
   - Understanding class imbalance between defaulters and non-defaulters
5. Univariate & Segmented Analysis
   - Analysing individual variables and their behaviour across default status
6. Bivariate Analysis
   - Exploring relationships between key variables
7. Correlation Analysis
   - Identifying top correlated variable pairs for defaulters and non-defaulters
8. Business Insights & Recommendations
   - Translating analytical findings into actionable insights

Key Insights
- Applicants with lower income and higher loan amounts show higher default risk
- Employment stability and education level significantly influence repayment behaviour
- Certain financial attributes behave differently for defaulters vs non-defaulters
- Default events are highly imbalanced, requiring careful interpretation of patterns

Business Recommendations
- Apply stricter checks for high loan-to-income ratios
- Adjust interest rates or loan limits for higher-risk profiles
- Incorporate key driver variables into credit scoring and risk models

How to Run the Project
1. Clone the repository
2. Download the datasets and place them inside the `data/` folder
3. Open `credit_risk_analysis.ipynb`
4. Run all cells sequentially

Key Learnings
- Applying EDA in a real-world financial risk scenario
- Handling missing data and imbalanced classes
- Translating analytical results into business decisions
- Communicating insights through visualisations and presentations

Author
Padma Sai Vayigandla
Data Science Learner
