#  Music Store Data Analysis using SQL

##  Overview
This project analyzes a Music Store relational database using SQL to uncover insights into customer behavior, sales performance, and music trends.

By querying multiple interconnected tables, this project demonstrates how raw data can be transformed into meaningful business insights.

---

##  Objectives
- Understand customer purchasing patterns  
- Identify top customers and revenue-generating cities  
- Analyze popular music genres and artist performance  
- Extract insights to support business decisions  

---

##  Dataset & Schema
The database consists of multiple relational tables:

**Core Tables:**
- Customer, Employee  
- Invoice, InvoiceLine  
- Artist, Album, Track  
- Genre, MediaType  
- Playlist, PlaylistTrack  

###  Relationships
- Customer → Invoice → InvoiceLine  
- Artist → Album → Track  
- Genre → Track  
- Employee → Customer  

---

##  Key Business Questions
- Who is the senior-most employee?  
- Which countries generate the most invoices?  
- What are the top 3 invoice values?  
- Which city generates the highest revenue?  
- Who is the best customer?  
- Who listens to Rock music?  
- Which artists produce the most Rock tracks?  
- Which tracks are longer than average?  
- How much does each customer spend on artists?  
- What is the most popular genre by country?  
- Who is the top customer in each country?  

---

## 🛠️ SQL Skills Demonstrated
- Joins (INNER, LEFT)  
- Aggregations (SUM, COUNT, AVG)  
- GROUP BY & HAVING  
- Subqueries  
- Window Functions  
- Sorting & Filtering  

---

##  Key Insights
-  Top markets: Brazil, France, Germany  
-  Most popular genre: Rock  
-  Top city: Prague (highest revenue)  
-  High-value customers significantly impact revenue  
-  Few artists dominate music sales  

---

##  Business Recommendations
- Focus marketing on high-performing regions  
- Offer loyalty rewards to top customers  
- Promote popular genres like Rock  
- Use personalized recommendations  
- Implement region-based marketing strategies  

---

##  Challenges
- Handling complex table relationships  
- Writing multi-table JOIN queries  
- Working with large datasets  
- Applying advanced SQL techniques  


---

##  Conclusion
This project highlights how SQL can be used to analyze structured data and generate actionable insights for improving business performance, customer engagement, and marketing strategies.

---

##  Authors

- Chiluveru Sharath Chandra  

---

##  Support
If you found this project useful:
-  Star this repository  
-  Fork it  
-  Share it  

---
