## MySQL Advanced      
The objectives of this project include:
* Creating tables with constraints
* How to optimize queries by adding indexes
* What is and how to implment stored procedures and functions in MySQL
* what is and how to implement views in MySQL
* What is and how to implement triggers in MySQL

### Resources   
The following resources are used in this project:  
* [MySQL cheatsheet](https://devhints.io/mysql)   
* [MySQL Performance: How to leverage MySQL database indexing](https://www.liquidweb.com/kb/mysql-optimization-how-to-leverage-mysql-database-indexing/)   
* [Stored Procedure](https://www.w3resource.com/mysql/mysql-procedure.php)  
* [MySQL Triggers](https://www.w3resource.com/mysql/mysql-triggers.php)   
* [MySQL Views](https://www.w3resource.com/mysql/mysql-views.php) 
* [Functions and Operations](https://dev.mysql.com/doc/refman/5.7/en/functions.html) 
* [Trigger syntax and Examples](https://dev.mysql.com/doc/refman/5.7/en/trigger-syntax.html)  
* [CREATE TABLE statements](https://dev.mysql.com/doc/refman/5.7/en/create-table.html)  
* [CREATE PROCEDURE and CREATE FUNCTION statements](https://dev.mysql.com/doc/refman/5.7/en/create-procedure.html)
* [CREATE INDEX statements](https://dev.mysql.com/doc/refman/5.7/en/create-index.html)  
* [CREATE VIEW statements](https://dev.mysql.com/doc/refman/5.7/en/create-view.html)  

### Tasks
* **Task 0:** Creatign a table `users`
* **Task 1:** Script that creates a table `users`
* **Task 2:** Script that ranks country origins of bands ordered by the number of fans
*  **Task 3:** Script list all bands with `Glam rock` as their main style, ranked by thier longevity
* **Task 4:** Script that creates a trigger that decreases the quantity of an item after adding a new order
* **TASk 5:** Script that creates a trigger that resets the attribute `valid_email` only when `email` has been changed
* **Task 6:** Script that creates a stored procedur `AddBonus` that adds a new correction for a student
* **Task 7:** Script that creates a stored procedure `ComputeAverageScoreForUser` that computes and store the avarage score for a student.
* **Task 8:** Script that creates an index `idx_name_first` on the table `names` and the first letter of `name`
* **Task 9:** Script that creates an index `idx_name_first _score` on the table `name` and the `score`
* **Task 10:** Script that creates a function `SafeDiv` that devides the first by the second number or returns 0 if the second number is equal to 0
* **Task 11:** Script that creates `need_meeting` that lists all students  that have scored under 80

