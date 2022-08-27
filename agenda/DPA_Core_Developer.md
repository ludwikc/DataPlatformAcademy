# DPA: Core Developer Course Agenda

Core Developer is T-SQL Querying crash course to get you up and running with databases

6 modules, 6 lessons each, 10 minutes at a time. 

1. Module 1
 - [ ] Getting started: environment / installation / cloud services / free labs
 - [ ] Client-server architecture
 - [ ] Connect and SELECT
2. Module 2
 1. Lesson 1
 2. Lesson 2
 3. Lesson 3
 4. Lesson 4
 5. Lesson 5
 6. Lesson 6
4.    




## Module 1
### Lesson 1
Client-server Architecture

* The easiest model of a DATABASE
* What are the ADVANTAGES of databases over e.g. Excel spreadsheet?
* What software do you need to do all of the exercises?
* Hint: you need just ONE to connect to ALL of the database engines, like MS SQL Server, Oracle, PostgreSQL, MySQL, SQLite and more! 
* How to view the data from any TABLE in any DATABASE. 
```sql
SELECT * FROM [object] 
SELECT * FROM Customer 
```

### Day 2
Focusing on data important to the end-user - data consumer, business analyst or decision maker.
Limiting data on vertical axis / selecting only the necessary columns.

```sql
SELECT * FROM Artist
SELECT * FROM Customer
SELECT FirstName FROM Customer  
SELECT FirstName, LastName, Phone, Country, State FROM Customer  
SELECT FirstName, LastName, Phone, Country FROM Customer
SELECT FirstName, LastName, Country, Phone FROM Customer
```
### Day 3
Focusing on **the way** the data important to the end-user

```sql
[...]
ORDER BY Country DESC, LastName ASC
```

### Day 4
Filtering data on vertical axis, the basics of the
```sql 
[...]
WHERE = 'search'
```
clause.


___
Current version of course materials: 
*April 04, 2022*
