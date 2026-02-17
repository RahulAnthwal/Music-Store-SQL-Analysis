# Music-Store-SQL-Analysis
Analyzing digital music store sales and customer trends using PostgreSQL

Digital Music Store SQL Analysis
Project Overview
This project performs a comprehensive analysis of a digital music store's database to uncover business insights regarding customer behavior, sales performance, and inventory trends. Using PostgreSQL, I queried a complex database consisting of 11 interconnected tables, including Invoice, Customer, Track, and Artist.

🛠️ Tools & Technical Challenges
Database: PostgreSQL

Interface: pgAdmin 4

Data Integrity: During the initial data load, I successfully resolved Error Code 500 and handled data type mismatches (specifically integer conversion errors) to ensure a clean, query-ready environment.

📊 Key Business Questions & Insights
1. Senior Management Hierarchy

Question: Who is the senior-most employee based on job title?

SQL Skill: Basic SELECT and ORDER BY.

Insight: Identifying the top of the organizational chart to understand reporting lines.

2. Market Analysis (Top Countries)

Question: Which countries have the most invoices?

SQL Skill: GROUP BY and COUNT.

Insight: The USA and Canada represent the highest transaction volumes, suggesting these are the most mature markets.

3. High-Value Customers

Question: Who is the best customer based on total spending?

SQL Skill: JOIN operations between Customer and Invoice tables with SUM aggregations.

Insight: By identifying the top spender, the store can implement targeted loyalty programs or VIP rewards.

4. Music Popularity by Genre

Question: What is the most popular music genre in each country?

SQL Skill: Advanced Common Table Expressions (CTEs) and Window Functions.

Insight: While Rock is globally dominant, local trends help in tailoring regional inventory and marketing campaigns.

📂 Project Structure
Music_Store_database.sql: The schema definition and data import script.

Music_Store_Query.sql: The complete library of analysis queries, ranging from basic filtering to advanced data transformations.

💡 Summary of Findings
Revenue Growth: The highest revenue is generated from the 26-35 age demographic, consistent with overall digital consumption trends.

Strategic Location: Cities like Prague show high per-customer spending, making them ideal candidates for local promotional events or "Music Fest" sponsorships.

Inventory Focus: Rock, Latin, and Metal are the top three genres by track sales, suggesting a focus on these genres for new arrivals.
