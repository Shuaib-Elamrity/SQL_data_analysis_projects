# Shuaib-Elamrity-The-Parch-_-Posey-Database_sql
### Built with

+ SQL Languages
	+ SQL

+ Tools
	+ MySQL Workbench
	+ pgAdmin
	+ DB Browser for SQLite
## [Parch & Posey - Data Analysis Project](https://github.com/Shuaib-Elamrity/SQL_data_analysis_projects)
PostgreSQL project for helping fictional company called Parch & Posey for 
+ managing the Orders, 
+ finding out the relationship with different Accounts
+ monitoring the performance of Sales Reps
+ etc.
# Fileds Include
## [Basic_sql_query.sql](Basic_sql_query.sql) 
#### IN this part i will try to answer some sample and direct questions  using some commands like
 SELECT.............    FROM...........    ORDER BY .............. WHERE 
 ####EX :
 1. Try writing your own query to select only the id, account_id, and occurred_at columns for all orders in the orders table.
 2.  earliest orders in the orders table. Include the id, occurred_at, and total_amt_usd.
 3. Pulls the first 10 rows and all columns from the orders table that have a total_amt_usd less than 500.
## [SQL_join_analysis.sql ](SQL_join_analysis.sql)
#### In this part I will using **JOIN**
> 

A SQL Join statement is used to combine data or rows from two or more tables based on a common field between them. Different types of Joins are: INNER JOIN. LEFT JOIN
#### Examples for kind of questions :
1. Try pulling all the data from the accounts table, and all the data from the orders table.
2. Provide a table that provides the region for each sales_rep along with their associated accounts. Your final table should include three columns: the region name, the sales rep name, and the account name. Sort the accounts alphabetically (A-Z) according to account name.
3. Provide the name for each region for every order, as well as the account name and the unit price they paid (total_amt_usd/total) for the order. Your final table should have 3 columns: region name, account name, and unit price. A few accounts have 0 for total, so I divided by (total + 0.01) to assure not dividing by zero.
4. Provide the name for each region for every order, as well as the account name and the unit price they paid (total_amt_usd/total) for the order. However, you should only provide the results if the standard order quantity exceeds 100 and the poster order quantity exceeds 50. Your final table should have 3 columns: region name, account name, and unit price. Sort for the largest unit price first. In order to avoid a division by zero error, adding .01 to the denominator here is helpful (total_amt_usd/(total+0.01).
## [Advanced]SQL Advanced JOINS.sql]([Advanced]SQL Advanced JOINS.sql)
## [Data_Cleaning.sql](Data_Cleaning.sql)

![P&P](https://raw.githubusercontent.com/ptyadana/sql-for-data-analysis/master/The%20Parch%20%26%20Posey%20Database%20ERD.png)

# Sources [Udacity_nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002)
