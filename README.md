# task7:Creating Views 
--Objective:
Learn how to create and use "views" in SQL to
Simplify complex queries (abstraction)
Enhance data security by restricting access to specific columns
Promote reuse of query logic

 SQL*Plus (Oracle SQL)
 EMP, DEPT tables
 view: Basic Employee Info
sql
CREATE VIEW EMP_VIEW AS SELECT EMPNO,ENAME,SAL FROM EMP;

SELECT * FROM EMP_VIEW;
we want drop the view then
drop view view_name;
Views with joins, aggregates, subqueries, and nested logic
Views used for data abstraction and security
Using DROP VIEW to delete virtual tables
Practical usage of ROWNUM, AVG(), SUM(), and other SQL functions
