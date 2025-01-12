# Multi-Table Relational SQL

### 1.Question 1
### What is the primary added value of relational databases over flat files?

`Ability to scan large amounts of data quickly`

### 2.Question 2
### What is the purpose of a primary key?

`To look up a particular row in a table very quickly`

### 3.Question 3
### Which of the following is NOT a good rule to follow when developing a database model?

`Use a person's email address as their primary key`

### 4.Question 4
### If our user interface (i.e., like iTunes) has repeated strings on one column of the user interface, how should we model this properly in a database?

`Make a table that maps the strings in the column to numbers and then use those numbers in the column`


### 5.Question 5
### Which of the following is the label we give a column that the "outside world" uses to look up a particular row?

`--Logical key`


### 6.Question 6
### What is the label we give to a column that is an integer and used to point to a row in a different table?

`Foreign key`

### 7.Question 7
### What SQLite keyword is added to primary keys in a CREATE TABLE statement to indicate that the database is to provide a value for the column when records are inserted?


`AUTOINCREMENT`

### 8.Question 8
### What is the SQL keyword that reconnects rows that have foreign keys with the corresponding data in the table that the foreign key points to?

`JOIN`

### 9.Question 9
### What happens when you JOIN two tables together without an ON clause?

`The number of rows you get is the number of rows in the first table times the number of rows in the second table`

### 10.Question 10
### When you are doing a SELECT with a JOIN across multiple tables with identical column names, how do you distinguish the column names?

`tablename.columnname`
