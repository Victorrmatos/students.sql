  # Students SQL
This repository contains SQL queries and sample data for a database of students.

  Table of Contents
1 Description
2 Sample Data
3 Queries
4 Usage

 1 Description
The purpose of this repository is to provide sample data and SQL queries for a database of students. 
The data consists of a single table with columns for student ID, name, email, and GPA. 
The SQL queries provided are intended to demonstrate common operations such as selecting, filtering, sorting, and joining data.

 2 Sample Data
The sample data is provided in a CSV file (students.csv) with the following columns:

id: The unique ID of the student.
name: The name of the student.
email: The email address of the student.
gpa: The grade point average of the student.
 
 3 Queries
The following SQL queries are included in this repository:

select_all.sql: Selects all columns and rows from the students table.
select_where.sql: Selects students with a GPA greater than or equal to 3.0.
select_join.sql: Joins the students table with a courses table to select the name of each student and the name of the course they are enrolled in.
select_groupby.sql: Groups the students table by GPA and calculates the average GPA for each group.
select_orderby.sql: Orders the students table by GPA in descending order.

4 Usage
To use the sample data and SQL queries in this repository:

Clone the repository to your local machine.
Open the students.sql file in your preferred SQL editor.
Run the SQL queries in your preferred database environment.
Note that you may need to modify the SQL queries to match the schema of your own database, or to use a different data source.
