2) Databases 101
What type of database should you consider using if the data you're going to be storing will vary greatly in its format? -Non-relational database
What type of database should you consider using if the data you're going to be storing will reliably be in the same structured format? -relational database
In our example, once a record of a book is inserted into our "Books" table, it would be represented as a ___ in that table? -row
Which type of key provides a link from one table to another? -foreign key
which type of key ensures a record is unique within a table? -primary key

3) SQL
What serves as an interface between a database and an end user? -DBMS
What serves as an interface between a database and an end user? -SQL

4) Database and Table Statements
Using the statement you've learned to list all databases, it should reveal a database with a flag for a name; what is it? -THM{575a947132312f97b30ee5aeebba629b723d30f9}
In the list of available databases, you should also see the  task_4_db database. Set this as your active database and list all tables in this database; what is the flag present here? -THM{692aa7eaec2a2a827f4d1a8bed1f90e5e49d2410}

5) CRUD Operations
Using the tools_db database, what is the name of the tool in the hacking_tools table that can be used to perform man-in-the-middle attacks on wireless networks? -Wi-Fi Pineapple
Using the tools_db database, what is the shared category for both USB Rubber Ducky and Bash Bunny? -USB attacks

6) Clauses
Using the tools_db database, what is the shared category for both USB Rubber Ducky and Bash Bunny?
SELECT DISTINCT category FROM hacking_tools; -6
Using the tools_db database, what is the first tool (by name) in ascending order from the hacking_tools table?
SELECT * FROM hacking_tools ORDER BY name ASC; -Bash Bunny
Using the tools_db database, what is the first tool (by name) in ascending order from the hacking_tools table?
SELECT * FROM hacking_tools ORDER BY name DESC; -Wi-Fi Pineapple

 7) Operators
Using the tools_db database, which tool falls under the Multi-tool category and is useful for pentesters and geeks?
SELECT * FROM hacking_tools WHERE category = “Multi-tool” AND description LIKE “%geeks%”; -Flipper Zero
Using the tools_db database, what is the category of tools with an amount greater than or equal to 300?
SELECT * FROM hacking_tools WHERE amount >= "300"; -RFID cloning
Using the tools_db database, which tool falls under the Network intelligence category with an amount less than 100?
SELECT * FROM hacking_tools WHERE category >= "Network intelligence" AND amount < "100"; -Lan Turtle

8) Functions
Using the tools_db database, what is the tool with the longest name based on character length?
SELECT name, LENGTH(name) AS name_length FROM hacking_tools ORDER BY name_length DESC; -USB Rubber Ducky
Using the tools_db database, what is the total sum of all tools?
SELECT SUM(amount) AS total FROM hacking_tools; -144
Using the tools_db database, what are the tool names where the amount does not end in 0, and group the tool names concatenated by " & ".
SELECT name, GROUP_CONCT(amount SEPARATOR "&") AS group FROM hacking_tools WHERE amount % 10 != 0 GROUP BY name; -Flipper Zero&iCopy-XS
