# MovieFlix-Repository-Exploration

Querying with SQL to Understand MovieFlix Database
---
(<img width="527" alt="image" src="https://github.com/user-attachments/assets/0fada015-a4f1-4a0b-b3c8-efc91f689039" />)

*Disclaimer⚠️: All datasets and reports do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual. All info are dummy and design to demonstrate my capabilities of using SQL to perform descriptive and diagnostic analytics.*

INTRODUCTION 
---
MovieFlix Rentals offers a diverse library of DVDs, from Hollywood blockbusters to indie favourites, with flexible rental plans to suit all viewers. We prioritize convenience through online reservations and local delivery/pickups options, ensuring an exceptional viewing experience. Committed to quality and customer satisfaction, we make every night a movie night.

<img width="288" alt="image" src="https://github.com/user-attachments/assets/c83d1f12-233c-4e96-921a-18b08987994b" />

PROBLEM STATEMENT 
---
MovieFlix Rentals has a DVD rental service tracks customer information, movie inventory, and rental transactions in its database. The database helps the company manage its operations efficiently by storing and retrieving data related to customers, movies, and rental activities.

AIM OF PROJECT 
--- 
* Query Data to see stored Data
* Explore Data to gather Insights
* Use Query Languages to manipulate data  

RATIONALE OF THE PROJECT
--- 
The task helps us understand MovieFlix database, by extracting meaningful insights from structured data, which is a key skill in data analysis and database  management. It also helps us familiarize ourselves with the company data so as to be readily equipped to answer their data related enquiries.

PROJECT WORKFLOW 
---
* Business Understanding: Understand the company's objectives and expectations to align analysis with business goals.
* Restore Database: Restore database to see the tables and what each columns contains in each tables
* Query Data : Querying the data from the company's database to understand it for in-depth analysis.
* Recommendations: Based on findings from the analysis, provide actionable insights and recommendations. 

SQL FUNCTIONS/CLAUSES
--- 
* SQL QUERIES: Extract relevant data from the database.
* CASE: Executes conditional logic by evaluating conditions and returning a value.
* JOIN: Combine rows from two or more tables based on a related column between them.
* COUNT: Returns the number of rows that matches a specified criterion.
* GROUP BY: Often used with aggregate functions to group the result-set by one or more columns.

TASK QUESTIONS 
--- 
* How can we classify customers into different spending tiers based on their total payments?
* What are the top 10 most rented movies, and how many times has each been rented?
* What is the average rental duration for each store, and how does it vary between stores?
* Which staffs processed the most rentals, and how much revenue have they handled?

### CUSTOMER SPENDING TIERS 
This query provides insights into the company's customer & spending data by grouping different customers into spending tiers with low spenders being <$70, med spenders being between $70-100 and high spenders being $100>. 

<img width="919" alt="image" src="https://github.com/user-attachments/assets/5865050d-a27d-4f35-a74b-2f56601527df" />

### MOST RENTED MOVIES AND TIMES IT HAS BEEN RENTED 
This query illustrates the movies that have been rented the most and the amount of times it has been rented. The analysis tells us that Bucket Brotherhood is the most rented movie with 34 being the amount of times it has been rented. 

<img width="919" alt="image" src="https://github.com/user-attachments/assets/5e536197-f5aa-4871-86af-5d3ef6970f70" />

### AVG RENTAL DURATION OF EACH STORE AND VARIANCE 
This analysis focuses on the average rental duration for each store, and how does it vary between stores. From the analysis below, we can see that both stores are close in  avg rental time but store 1 is perfoming better than store 2 on a small margin. This could be due to various reasons which will be mentioned in recommendations. 

<img width="917" alt="image" src="https://github.com/user-attachments/assets/7e2ee0fe-a129-473f-97b6-d6040808fe33" />

### STAFF REVENUE AND RENTALS 
This query gives on an insight on which staffs processed the most rentals, and how much revenue have they handled. This query shows us that Mike Hillyer and Jon Stephens are the top 2 staffs who had the most rentals and revenue with Mike having the most number of rent and generating the most revenue. 

<img width="919" alt="image" src="https://github.com/user-attachments/assets/60b1ece3-6a57-49c2-b9cb-8c78164cce1e" />

RECOMMENDATIONS
--- 
Based on the insights drawn from the dataset, here are some data-driven recommendations:
* Invest more in advertising campaigns for movies that are rented the most to generate more revenue.
* Perform customer surveys to know the genre of movies customers would like to rent.
* Offer promotional discounts as an incentive for customers who rent often. 

By applying these recommendations, MovieFlix will be able to maximise profit and generate more revenue. 

### THANK YOU
For more information, you can contact me
![Orange Modern Technology LinkedIn Banner](https://github.com/user-attachments/assets/4d91e1e5-c613-48a0-8a9a-15dbaf997908)



























