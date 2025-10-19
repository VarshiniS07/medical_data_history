🏥 Medical Data Analysis Project

📘 Overview

This project explores medical data to uncover insights about patient demographics, admissions, diagnoses, and doctor performance using SQL and Power BI.
It aims to simulate real-world healthcare analytics — where SQL is used to query, clean, and analyze data stored in a relational database, and Power BI is used to visualize the results in an interactive dashboard.

🎯 Key Insights (From Dashboard & SQL Analysis)

Total Patients: 1,000+ across multiple provinces and cities.

Gender Distribution: Balanced with a slightly higher percentage of females

Most Common Diagnoses: Dementia, Epilepsy, Hypertension.

Admission Trends: High admissions between ages 36–55 and seniors(56-75)

Same-day Admissions: Few cases indicate efficient treatment processes.

Allergies: ‘NKA’ (No Known Allergies) is the most frequent entry after data cleaning.


Top Cities: Certain cities in province ‘NS’ had the highest patient count.



🧠 Tools & Techniques Used

Category	Tools / Methods
Database	MySQL
Querying	SQL (SELECT, JOIN, GROUP BY, HAVING, UNION, UPDATE)
Visualization	Power BI
Data Cleaning	Null handling, string pattern matching, derived columns
Analysis Techniques	Aggregations, Conditional Logic, City/Province-level grouping
Version Control	Git & GitHub

🗂️ Project Structure

medical-data-analysis/
│
├── sql/
│   ├── 01_queries.sql         # 34 SQL questions & solutions
│
├── powerbi/
│   ├── medical_dashboard.pbix  # Power BI file (if size < 50 MB)
│   ├── screenshots/
│   │   ├── dashboard_overview.png
│   │   ├── gender_insights.png
│   │   └── diagnosis_trends.png


⚙️ How to Use This Project

Clone or Download Repository

git clone https://github.com/VarshiniS07/medical-data-history.git
cd medical-data-history

Run SQL Queries

Open MySQL Workbench (or any SQL IDE).

Import schema.sql (if available).

Load the database using project_medical_data_history.

Execute queries from sql/01_queries.sql.

Open Power BI Dashboard

Open medical_dashboard.pbix.

Refresh data source connection if required.

Explore visuals such as patient demographics, admission counts, diagnosis trends, and BMI distribution.

View Results

SQL results → Query output.

Power BI visuals → Dashboard insights.

🚀 Future Improvements

Add interactive filters (age group, province, diagnosis type) in Power BI.

Connect Power BI directly to MySQL database for live refresh.

Include predictive analysis using Python (e.g., predicting admission probability).

Add a data dictionary and ER diagram for better schema understanding.

Automate data cleaning using stored procedures or Power Query.

Deploy Power BI dashboard to Power BI Service and share via public link.

👩‍💻 Author

Varshini S
Aspiring Data Analyst | Skilled in SQL, Power BI, and Data Visualization
https://github.com/VarshiniS07
