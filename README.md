SQL Projects
Welcome to my SQL Projects repository! This repo contains a collection of SQL scripts and queries that demonstrate various techniques, data analysis, and problem-solving approaches using SQL.

Table of Contents
Introduction
Projects Overview
Technologies Used
How to Run
File Structure
Contributions
License
Introduction
This repository showcases SQL projects that I've worked on to practice and demonstrate my skills in SQL. The projects cover topics like data manipulation, aggregation, joins, window functions, and more advanced topics like optimizing queries, working with views, and stored procedures.

Projects Overview
1. Video Game Industry Analysis
The global gaming market is projected to surpass $300 billion by 2027. 
This project analyzes video game critic and user scores along with sales data for the top 400 games since 1977.
You will search for a "golden age" of video games by identifying release years that received the best scores and explore the business side by analyzing game sales.
 
Key Concepts: Dataset joins, set theory, filtering, grouping, and ordering data.
Tables Used:
   - `game_sales`: Video game sales by name, platform, and year.
   - `reviews`: Critic and user scores from Metacritic.
   - `users_avg_year_rating` and `critics_avg_year_rating`: Average scores per year.  
Skills: `JOIN`, `GROUP BY`, `ORDER BY`, Set Theory.
   
2. Mental Health and International Students
A Japanese university conducted a survey in 2018 to analyze the mental health of international students.
This project explores the survey data to find if international students face more mental health difficulties than domestic students.
You'll focus on factors like social connectedness, depression, and length of stay.
Key Concepts: Statistical analysis of survey data, categorization of students based on language proficiency and academic status.  
Table Used:
  - `students`: Data on language proficiency, academic level, and mental health scores of international and domestic students.  
Skills:`GROUP BY`, `SUM()`, `AVG()`, statistical queries.

3.Motorcycle Parts Sales Analysis
Your company sells motorcycle parts across three warehouses and is looking for insights into its sales. 
This project calculates net revenue for different product lines, grouped by month and warehouse, with a focus on wholesale orders. 
You'll analyze the `sales` table, filter data for wholesale clients, and account for different payment methods and associated fees.
Key Concepts:** Revenue analysis, grouping by multiple fields, filtering by client type.
Table Used:
 - `sales`: Sales data, including product type, warehouse location, client type (wholesale or retail), and payment methods.
Skills:** `GROUP BY`, `WHERE`, `SUM()`, `DATE_PART()`.

4. International Debt Analysis
This project focuses on analyzing international debt data collected by The World Bank.
You will answer questions related to the number of countries in debt, the country with the highest debt, and the country with the lowest repayment amounts.
 The dataset contains information about debt indicators across various developing nations.
Key Concepts:** Aggregating debt data by country and debt indicator.
Table Used:
  - `international_debt`: Details of debt held by countries across different indicators.
Skills: `COUNT()`, `MAX()`, `MIN()`, `GROUP BY`.

Technologies Used
SQL Dialects: PostgreSQL, MySQL, SQLite
Data Sources: Sample databases, CSV files
How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/sql-projects.git
Install the required SQL database system (e.g., PostgreSQL or MySQL).

Run the scripts in your preferred SQL tool (pgAdmin, MySQL Workbench, etc.).

Modify the database connection settings in the scripts if necessary to match your setup.
