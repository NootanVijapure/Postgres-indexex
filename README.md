here are exercises to practice creating single-column, multi-column, and unique indexes in PostgreSQL:

Single Column Index Exercise:

Create a table named students with the following columns:

student_id (integer)
student_name (text)
age (integer)
Exercise: Create a single-column index on the student_id column.

Multi-Column Index Exercise:

Expand the students table by adding two more columns:

course_id (integer)
enrollment_date (date)
Exercise: Create a multi-column index on the course_id and enrollment_date columns.

Unique Index Exercise:

Add one more table named courses with the following columns:

course_id (integer)
course_name (text)
Exercise: Create a unique index on the course_id column in the courses table.

You can use the EXPLAIN command in PostgreSQL to analyze the execution plan of a query and check the performance with and without indexes for each queries
