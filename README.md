# PL-SQL-GRPWork-
a simple working solution in MySQL (XAMPP compatible) for your class quiz. we’ll use an example with Students and Courses tables

# Class Quiz – Database Assignment

This project is an MySQL database exercise done as a class quiz. It covers creating tables with constraints, inserting data, performing joins, creating an index, and making a view.

## What I Did

1. **Created Tables** – `students`, `courses`, and `enrollments` with primary keys, foreign keys, unique email, and not null constraints.
2. **Inserted Data** – Added sample students, courses, and enrollments.
3. **Performed Joins** – Tested INNER, LEFT, RIGHT, and FULL (via UNION) joins to understand differences in results.
4. **Created Index** – Added a composite index on `(student_id, course_id)` to speed up queries.
5. **Created View** – Built `student_course_grades` to simplify access to student, course, and grade info.

## Screenshot

<img width="661" height="137" alt="dbms" src="https://github.com/user-attachments/assets/26ec8c96-985b-4910-9aa0-07877f987c3c" />

##  Conclusion

This task helped us to practice key database concepts:

* Constraints keep data clean and consistent.
* Joins show different perspectives of related data.
* Indexes improve performance.
* Views make queries easier to use.
