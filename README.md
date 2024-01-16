# Description
The Student Management System is a Python-based application that facilitates the efficient management of student data. 
It utilizes a MySQL database to store information about students, courses, and grades.

# Prerequisites
Before running the Student Management System, ensure you have Python installed. 
Additionally, set up a MySQL database and configure the connection details in the system.

# Installations
1. Clone the repo: <br>
   `git clone https://github.com/your-username/student-management-system.git`

2. Install Python dependencies: <br>
   `pip install PyQt6`

3. Set up the MySQL database:

* Create a new database.
* Import the provided SQL schema file.

# Usage

1. First download MySQL from the official site: [MySQL](https://dev.mysql.com/downloads/mysql/)
2. Create a database with any name of your choice. (My database name is studentManagement)
   `CREATE DATABASE name_of_your_database;`
3. Create a table in the database named "students". (This has to be the same, otherwise it will give **no database found error**) <br>
Use the following commands for creating a database and a table inside the same: <br>   
   * `USE name_of_your_database` This is for using the database where you want to create the table. <br>
   * `CREATE TABLE students (id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255), course VARCHAR(255), mobile VARCHAR(255));` This command will create a table with the columns id, name, course, mobile.
4. Then in the IDE type the following command in the terminal: <br>
   `python main.py`
---
> "SQL is like a fine wine – it gets better with time."
