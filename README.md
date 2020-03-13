# Query Sakila Movie Database 

The **Sakila Movie database** is a SQL database of online DVD rentals.  The goal query the database to answer questions about business decisions. This project, is querying the database to gain an understanding of the customer base, such as what the patterns in movie watching are across different customer groups, how they compare on payment earnings, and how the stores compare in their performance. The ER Diagram was provided in `dvd-rental-erd-2.pdf`. 

Use SQL to explore a database related to movie rentals. This project uses: SQL joins, aggregations, subqueries & temporary tables, data cleaning, windows functions and SQL Advanced Joins & Performance Tuning.

## Statistics Computed: 
1. Q1. How many times the movies have been rented out in the family movies category? 
   - The following categories are considered family movies: Animation, Children, Classics, Comedy, Family and Music.

2. Q2. How many movies are there within each film category for each quartile? 
   
3. Q3. Who were the top 10 paying customers? and how many payments they made on a monthly basis during 2007, and what was the amount of the monthly payments?
   
4. Q4. For each of the top 10 paying customers, What is the difference across their monthly payments during 2007?

## Required Software

-  PostgreSQL: is an object-relational database management system. Object-relational databases use a hybrid approach to databases. Importantly, PostgreSQL allows the use of advanced functions (such as Window Functions), and even development and use of custom functions written in different programming languages. 

1. Install PostgreSQL: 
    - Install for [windows]
    - Install for [maxos]
2. Download [Sakila Database]  
3. Load the databse: check this link [Load PostgreSQL Sample Database]
4. Connecting back to the PostgreSQL server: Relaunch PgAdmin III and click on the PostgreSQL server within the Object browser.
5. Connecting to the DVD rental database: Next click on the plus sign next to Databases to access the DVD rental database. 
6. Choose the DVD Rental database: Choose the dvdrental database under Databases. 
7. Running Queries on your dvdrental database: Click on the SQL icon and run your queries
  
## Credits
All credits go for data science nanodegree program offered by Udacity.

[windows]: <http://www.postgresqltutorial.com/install-postgresql/>

[maxos]: <https://www.postgresql.org/download/macosx/>

[Sakila Database]: <https://www.postgresqltutorial.com/postgresql-sample-database/>

[Load PostgreSQL Sample Database]: <https://www.postgresqltutorial.com/load-postgresql-sample-database/>
