Music Store Data Analysis using SQL
Overview

This project focuses on analyzing a Music Store database using SQL to extract meaningful insights about customer behavior, sales trends, and music preferences.

The dataset contains multiple related tables such as customers, invoices, artists, albums, and tracks, allowing for deep relational analysis.

Objectives
Analyze customer purchasing behavior
Identify top customers and high-revenue cities
Discover most popular music genres
Evaluate artist and track performance
Generate business insights using SQL queries
Database Schema

The database consists of the following key tables:

Customer
Employee
Invoice
InvoiceLine
Artist
Album
Track
Genre
MediaType
Playlist
PlaylistTrack
🔗 Relationships
Customer → Invoice (One-to-Many)
Invoice → InvoiceLine (One-to-Many)
Artist → Album → Track (One-to-Many)
Genre → Track
Employee → Customer

Key Analysis Questions
Who is the senior-most employee?
Which countries have the most invoices?
What are the top 3 invoice totals?
Which city generates the highest revenue?
Who is the best customer?
List all Rock music listeners
Top 10 artists with most Rock tracks
Tracks longer than average duration
Amount spent by each customer on artists
Most popular genre by country
Top customer in each country

SQL Concepts Used
SELECT statements
JOINs (INNER, LEFT)
GROUP BY & HAVING
Aggregate functions (SUM, COUNT, AVG)
Subqueries
Window functions
ORDER BY & LIMIT

Key Insights
Top revenue-generating countries: Brazil, France, Germany
Rock is the most popular music genre
Prague is the highest revenue-generating city
High-value customers contribute significantly to sales
A few artists dominate the Rock genre

Business Recommendations
Focus marketing on top-performing countries
Provide loyalty rewards to high-spending customers
Promote Rock music and top artists
Use personalized recommendations
Run region-based marketing campaigns

Challenges Faced
Understanding relationships between multiple tables
Writing complex JOIN queries
Handling large datasets
Using advanced SQL functions
Ensuring accurate aggregations

Project Structure
Music-Store-SQL-Analysis/
│── dataset/
│── queries/
│── outputs/
│── presentation/
│── README.md
📎 Project Presentation

You can view the project presentation here:
Music Store Data Analysis PPT (uploaded)

Conclusion

This project demonstrates how SQL can be used to analyze relational data and extract valuable business insights. The findings can help improve decision-making, marketing strategies, and customer engagement.

Acknowledgements

This project was developed as part of academic learning to strengthen SQL and data analysis skills.

Author
Chiluveru Sharath Chandra
