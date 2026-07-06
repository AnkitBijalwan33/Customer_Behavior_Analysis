📊 Customer Shopping Behavior Analysis
📝 Overview
An end-to-end data analytics project that builds a robust data pipeline to transform raw, unstructured transactional data into strategic business insights. The project covers data ingestion, automated database pipeline creation, advanced SQL analytics, and interactive dashboard modeling to optimize store performance and subscription strategies.

📅 Dataset
The project analyzes a retail dataset containing 3,900 transactions across multiple consumer features:

Size: 3,900 rows and 18 columns.

Key Features: Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount (USD), Location, Size, Color, Season, Review Rating, Subscription Status, Shipping Type, Discount Applied, Promo Code Used, Previous Purchases, Payment Method, and Frequency of Purchases.

🛠️ Tools & Technologies Used
Data Cleaning & EDA: Python (Pandas, NumPy, Matplotlib, Seaborn)

Database & Pipelines: MySQL Workbench / PostgreSQL (sqlalchemy & pymysql)

Data Visualization & Modeling: Power BI Desktop (DAX Modeling)

Presentation & Reporting: Gamma AI

🏃‍♂️ Project Architecture & Steps
1. Data Cleaning & Feature Engineering (Python)
Handled missing values using statistical techniques (Median Imputation for Review Rating).

Standardized text entries and mapped purchase frequencies (e.g., Weekly, Monthly) into explicit numeric intervals.

Engineered a custom age_group classification (Young Adult, Adult, Middle-aged, Senior) to segment consumer behavior efficiently.

2. Database Integration & Validation (SQL)
Developed an automated ingestion pipeline using sqlalchemy to export cleaned Python data straight into the SQL database.

Executed advanced validation queries utilizing Common Table Expressions (CTEs) and Window Functions (ROW_NUMBER) to cross-verify structural data integrity.

3. Interactive Visualization (Power BI)
Imported the verified relational tables from SQL into Power BI.

Wrote optimized DAX Measures for dynamic high-level KPI tracking (Total Customers, Avg Purchase, Avg Rating).

Built interactive dimensional filters allowing stakeholders to drill down by Gender, Category, Shipping Type, and Subscription status.

4. Executive Reporting (Gamma AI)
Utilized Gamma AI to generate a clean, executive-level corporate presentation summarizing key findings for business leadership.

📊 Dashboard Snapshot
![Customer Behavior Dashboard](images/dashboard.png)
