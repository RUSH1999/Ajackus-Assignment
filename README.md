# Ajackus-Assignment
# An explanation of how the assistant works.
1) Set up the SQLite database with Employees and Departments tables.
2) Created a Python script using sqlite3 to interact with the database.
3) Generated SQL queries dynamically based on user input which is provided by Ajackus and also included some more queries for better results.
4) Fetched data from SQLite and format the response in user understanding.
5) Implemented error handling to manage invalid queries.

# Steps to run the project locally.
1) First Run setup_db.py, once to create and populate the database.
2) Second Run chatbot.py to start the chat assistant.

# The chat assistant supports the following types of queries.
# Examples:
1) Show me all employees in the Engineering department.
2) Who is the manager of the Sales department?
3) List all employees hired after 2021-01-01.
4) What is the total salary expense for the Marketing department?
5) What is the highest salary in the Engineering department?
6) What is the lowest salary in the Sales department?
7) What is the highest and lowest salary in the Marketing department?
8) What is the highest salary in all the departments?
9) List all departments.
10) List all the employees.
11) Show complete data of Employees.
12) Show complete data of Departments.

# For Exceptional Queries
1) Show me all employees in HR.
2) Who is the manager of HR?

# Known limitations or suggestions for improvement.
**Limitations** is we have to manully create a SQL query for the user understanding and user have to enter same query for there desired results.
**suggestions for improvement** is we can add more types of detailed query for the better response to the users questions or we can use some AI APIs in the project.
