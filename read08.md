# SQL
- Structred Query Language (said SEE QUIL)
- Communicates with database
- A way to get files from the database
- Only talks to ***relational*** database - datatable with ***rows and columns***
- Many types of SQL databases
    - SQLite
    - MySQL
    - Postgres
    - Oracle

# SQLBolt Lessons:
## SELECT   
statements - also called ***queries***  
- declares what data we're looking for.  
**column = properties**/**rows = instances**
SQL Format:  
    `SELECT column FROM database;` - can add more columns with a comma.  

## WHERE   
filters out whats being returned - applies to the rows of the column being queried. Uses logical operators to construct more complex clauses.
``AND/OR``
SQL Format:  

SELECT column, another_column, …  
FROM mytable  
WHERE condition  
    AND/OR another_condition  
    AND/OR …;

*Writing clauses also helps return data faster by filtering out unconditional queries*

## Operators 
Numbers   
    -``=,!=,< <=, >, >=`` = standard numerical operators
    -``BEWTEEN... AND ..`` = Number is within range of two values (inclusive)  
    -``NOT BETWEEN … AND …`` = Number is not within range of two values (inclusive)  
    - ``IN(...)`` = Number exists in a list  
    - ``NOT IN (...)`` = Number does not exist in a list

## QUERIES AND CONSTRAINTS
Case sensitive strings/alphas    
    -``=`` = Case sensitive exact string comparison (notice the single equals)  
    -``!= or <>`` = Case sensitive exact string inequality comparison  	
    -``LIKE`` = 	Case insensitive exact string comparison  
    -``NOT LIKE`` = Case insensitive exact string inequality comparison  
    -``%`` = Used anywhere in a string to match a sequence of zero or more characters (only with LIKE or NOT LIKE)  
    -``-`` = Used anywhere in a string to match a single character (only with LIKE or NOT LIKE)  
    -``IN (...)`` = String exists in a list	  
    -``NOT IN (...)`` = String does not exist in a list  

## MORE FILTERING
``DISTINCT`` - discards rows with duplicate column value.  
``ORDER BY`` - orders queries by ASC/DESC  
``LIMIT`` - rows returns in querey
``OFFSET`` - tells where to start counting LIMIT

# PEMDAS FOR SQL
1. FROM
2. WHERE
3. GROUP BY
4. HAVING
5. SELECT 
6. DISTINCT
7. ORDER BY
8. LIMIT/OFFSET

