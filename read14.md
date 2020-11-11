# Database Normalization  
- process used to organize a database into tables and columns.  
- this helps with recalling information and traversing the data.  
- Gives tables single uses and allows for reduction in duplicate data.
- Needs to use established rules to follow.  

   
*What is database table?*   
- *where all data is stored in a database*  
- *tables are made up of rows and columns*

### 3 Main Reasons for Database Normalization  
1. Minimize duplicate data  
2. avoid data modification issues  
3. simplify queries  

*Modification Anomalies are when we need to update something and other things need update/fix etc - just code as normal*  
### Insert Anomaly  
- Facts that can't be recorded until all data in a row is known
### Update
- If single change happens multiple elements must be updated
### Deletion
- If single data column is deleted - it may clear out all other data related to the single.  

## Search and Sort Issues
*If data stays on a single table like normal excel stuff - search queries will need lots of union queries*

Process to refactor/redesign the table is database normalization

## Three Normal Forms  
- as you go through forms the data gets more optimized...whatever that means?  
- Forms are progressive - meaning you must pass 1NF to move to 2NF and so on.

1.  The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.  
2.  The table is in first normal form and all the columns depend on the table’s primary key.  
3.  the table is in second normal form and all of its columns are not transitively dependent on the primary key