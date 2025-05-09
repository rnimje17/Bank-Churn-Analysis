# Bank Churn Analysis Dashboard 💹

## 1. Title
**Bank Churn Analysis Dashboard** 💼

## 2. Short Description / Purpose
This project analyzes bank churn data to understand customer attrition patterns and identify areas for retention improvement. Leveraging Power BI 📊, the dashboard walks through the entire data lifecycle—from connection and cleaning 🧹 to modeling and visualization—transforming raw bank customer data into actionable business insights. The interactive visualizations help stakeholders quickly grasp trends, measure performance 📈, and drive strategic decisions.

## 3. Tech Stack
- **Data Visualization & Reporting:** Power BI (PBIX) 🖥️
- **Data Modeling & Calculations:** DAX (Data Analysis Expressions) ✍️
- **Data Preparation & Cleaning:** Power Query, Microsoft Excel 🧹
- **Data Source Integration:** SQL/Data Connectors within Power BI 🔗

## 4. Data Source
- **Dataset:** A sample bank churn dataset tailored for analysis 📁.
- **Contents:** The dataset includes demographic details, credit scores, account balances, credit card ownership status, activity status, churn indicators, and product usage.
- **Notes:** The data undergoes thorough cleaning and transformation—such as removing the 'Estimated Salary' column, standardizing column names, and creating conditional columns (e.g., Age Group, Credit Scores, Account Balance)—to ensure accurate modeling and visualization.

## 5. Features & Highlights
- **Data Cleaning & Transformation:**  
  - Verified data types, standardized column names (ensuring each starts with a capital letter), and removed unnecessary fields.
  - Created additional columns for better segmentation, such as Age Group, Credit Scores buckets, and Account Balance ranges.
  - Built reference tables for Age Groups, Credit Scores, and Account Balances with unique identifiers for robust analysis.
  
- **Modeling & DAX Measures:**  
  - Constructed key measures using DAX to calculate Total Customers, Lost Customers, and Churn Rate (currently displayed as 25.6% on the dashboard) 🔢.
  - Enabled dynamic filtering and slicing of data across multiple dimensions.

- **Interactive Visualizations:**  
  - **Key Metrics Cards:** Display overall numbers—Total Customers (7,963), Lost Customers (2,037), and Churn Rate—for a quick summary at a glance.
  - **Charts & Graphs:**  
    - **Pie Charts:** Visualize distributions by Gender, Active Status (Active/Inactive), Credit Card Ownership (Owned/Not Owned), Country (e.g., Germany, Spain, France), and Churn Status.
    - **Bar/Line Charts:** Show detailed customer counts and churn rates across different Age Groups (<20, 21-30, …, >71) and Credit Score ranges (e.g., ≤400, 401-500, 601-700, etc.) 📊.
    - **Line Graphs:** Illustrate lost customers segmented by Country and Gender.
    - **Stacked/Clustered Visuals:** Present breakdowns of customers by product names (e.g., Prod1, Prod2, Prod3), providing insights into product performance.
    
- **Report Sharing & Collaboration:**  
  - The dashboard is designed for easy sharing and distribution, enabling stakeholders to interactively explore the data and derive their own insights 📨.

## Dashboard Explanation
The **Bank Churn Analysis Dashboard** is an interactive medium to visualize critical aspects of customer attrition. With a clear layout showcasing key metrics like the total number of customers (7,963), lost customers (2,037), and a churn rate of 25.6%, this dashboard provides an at-a-glance performance snapshot. The diversity of visualizations—from pie charts and bar graphs to line charts—empowers multi-dimensional insights, such as:

- **Demographic Analysis:** Understanding how variations in age groups and credit score ranges influence churn.
- **Customer Behavior:** Assessing the impact of active versus inactive statuses and credit card ownership.
- **Geographical Trends:** Evaluating churn and customer distribution by country to identify market-specific challenges 🌍.
- **Product Insights:** Analyzing customer distribution by product to assess performance and preferences.

Dashboard Preview: https://github.com/rnimje17/Bank-Churn-Analysis/blob/main/Snapshot%20of%20Bank%20Churn%20Analysis%20Dashboard.png
