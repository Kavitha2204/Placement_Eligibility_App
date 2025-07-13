# 📊 Placement Eligibility Streamlit App


**1. Objective / Problem Statement**

Design and implement a Streamlit application where users can input eligibility criteria for placement. The application should query a dataset of student information and display details of eligible candidates dynamically.

**2. Technologies Used**

Python

Streamlit

SQLite3

Pandas

Faker (for generating synthetic data)

**3. Key Skills Applied**
Building dashboards with Streamlit

Generating fake datasets using Faker

SQL table creation and queries

Object-Oriented Programming (OOP)

Data filtering and visual exploration using Pandas

Database integration with SQLite

4. Project Flow / Architecture
Step 1: Data Generation
Created 4 major tables:

students – student profile data

enrollments – courses and enrollment dates

scores – performance scores per subject

attendance – last 30 days of attendance logs

Used Faker to generate realistic fake data

Ensured all tables are connected via student_id (foreign keys)

Step 2: Data Storage
Stored data in SQLite relational database

Used Python OOP for code modularity and clarity

Step 3: Streamlit Dashboard
Sidebar lets users select the table they want to view

Displayed data dynamically using st.dataframe()

Querying handled using pandas.read_sql_query()

5. Business Use Cases
Placement Management: Shortlist students based on performance

Student Performance Tracking: Visualize coding and soft skills readiness

Interactive Analytics: Enable non-tech users to analyze data easily

🔎 7. Example SQL Queries (Insights Section)
You can optionally include a few sample SQL queries such as:

sql
Copy
Edit
-- Top 5 students by overall programming score
SELECT student_id, SUM(score) as total_score
FROM scores
GROUP BY student_id
ORDER BY total_score DESC
LIMIT 5;
📁 8. Project Files
SQL_Table_Creation.py: Creates SQLite tables

SQL_Table_Generator.py: Generates fake student data

Streamlit_Application.py: Dashboard code

students.db: SQLite database with all 4 tables

📊 9. Sample Outputs
Add screenshots like:

Dashboard UI

Filtered results table

Sample SQL query outputs (optional)

📏 10. Evaluation Metrics
Functionality & Filtering

UI/UX of the dashboard

Code modularity and OOP structure

Insights quality via SQL

Completeness of documentation

✅ 11. Conclusion
This project demonstrates how to combine Python, SQL, and Streamlit to create an interactive eligibility analysis tool. The modular design allows for extension into real placement dashboards or academic analytics.


## ✨ Author

Created by [Kavitha] — part of the GUVI Capstone Project.
