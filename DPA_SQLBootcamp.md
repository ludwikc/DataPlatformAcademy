# SQLBootcamp Course Agenda

SQLBootcamp is a 1-hour crash course to get you up and running with databases

4 days, 15 minutes each day: 

### Day 1

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
