
# 💼 JOBORA – Online Job Portal


## 📌 Overview

JOBORA is a **database-driven job portal system** designed to connect **job seekers and employers**. This project focuses purely on **backend DBMS concepts** using SQL, without any web development.

It demonstrates real-world database design including **tables, relationships, constraints, stored procedures, and views**.

---

## 🎯 Features

* 👤 User management (Job Seekers & Employers)
* 💼 Job posting by employers
* 🔍 Job search functionality
* 📄 Job application system
* 🔄 Application status tracking
* ⚙️ Stored procedures for automation
* 📊 View for monitoring job applications

---

## 🗂️ Database Structure

### Main Tables:

* **Users** – Stores user details (seeker/employer)
* **JobSeekers** – Skills, experience, location
* **Employers** – Company details
* **Jobs** – Job postings
* **Applications** – Job applications
* **JobCategories** – Categories of jobs

---

## ⚙️ Functional Components

### 🔹 Stored Procedures

* `ApplyForJob` → Apply to a job (checks duplicate)
* `UpdateApplicationStatus` → Approve/Reject applications
* `SearchJobs` → Search jobs by keyword, location, skills

### 🔹 View

* `JobApplicationStatus` → Displays:

  * Job title
  * Applicant name
  * Application status

---

## 🛠️ Technologies Used

* SQL (MySQL)
* DBMS Concepts
* Relational Database Design

---

## 🚀 How to Run

1. Open MySQL / any SQL environment
2. Create database:

   ```sql
   CREATE DATABASE JOBORA;
   USE JOBORA;
   ```
3. Run the full SQL script (provided in repo)
4. Execute stored procedures for testing:

   ```sql
   CALL SearchJobs('Developer', 'Bangalore', NULL);
   CALL ApplyForJob(1, 2);
   ```

---

## 📊 Sample Operations

* Add users, jobs, and applications
* Search jobs using filters
* Apply for jobs
* Update application status
* View application results

---

## 📈 Learning Outcomes

* Database design (ER → Relational Model)
* SQL (DDL, DML, Constraints)
* Joins & Queries
* Stored Procedures & Views
* Real-world DBMS implementation

---
