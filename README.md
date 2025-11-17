# 📚 Spring Boot Java – Course Registration System

A simple **Spring Boot + MySQL** application for managing courses and course registrations.

---

## 📌 Database Setup

### 1️⃣ Create the Database

CREATE DATABASE course_reg_sym;
2️⃣ Insert Seed Data (Run After Application Starts)
The tables will be automatically created by Spring Boot, so you only need to run the insert commands:


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

## 📌 API Endpoints
Replace {url} with your base server URL
(e.g., http://localhost:8080 or deployed URL)

▶️ Get All Courses
GET {url}/courses

▶️ Get All Enrolled Students
GET {url}/courses/enrolled

▶️ Register for a Course
POST {url}/courses/register?name={name}&emailId={emailId}&courseName={courseName}
Example:
POST {url}/courses/register?name=sanjeev&emailId=sanjeev@example.com&courseName=MERN%20Stack

## ⚙️ Running the Application
▶️ Start the Spring Boot App
./mvnw spring-boot:run

🏗️ Build the Project
./mvnw clean install

## 🛠️ Tech Stack
Java
Spring Boot
MySQL
Maven
