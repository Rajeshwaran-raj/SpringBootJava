# SpringBootJava

**Create DB** in MySQL:
```sql
CREATE DATABASE course_reg_sym
```

**Insert Queries** for "course" Table
```sql
INSERT INTO `course_reg_sym`.`course`
(`course_id`, `course_name`, `duration_in_weeks`, `trainer`)
VALUES
(1, 'Java Fundamentals', 6, 'Rajesh Kumar'),
(10, 'Mobile App Development', 10, 'Priya Kapoor'),
(2, 'Spring Boot Basics', 8, 'Anita Sharma'),
(3, 'Python for Data Science', 10, 'Vikram Desai'),
(4, 'Web Development with React', 7, 'Meena Reddy'),
(5, 'Machine Learning Intro', 12, 'Arun Gupta'),
(6, 'Cloud Computing with AWS', 9, 'Pooja Iyer'),
(7, 'DevOps Essentials', 6, 'Ravi Nair'),
(8, 'Database Design with MySQL', 5, 'Suman Rao'),
(9, 'Cybersecurity Basics', 4, 'Deepak Sen');

```