 Student Management System - SQL Project

![MySQL](https://img.shields.io/badge/MySQL-8.0+-blue?logo=mysql)
![GitHub](https://img.shields.io/github/license/ShoaibAsim14/student-management-sql)

A comprehensive MySQL database solution for tracking and analyzing student academic performance.

Features

- Database Schema: Clean table structure with constraints
- Sample Data: 10 realistic student records
- Advanced Queries:
  - Performance analysis by subject/gender
  - Top performer identification
  - Grade distribution statistics
- Dynamic Updates: Modify student records easily

Database Schema

CREATE TABLE Students (
    StudentID INT AUTO_INCREMENT PRIMARY KEY,
    Name VARCHAR(50) NOT NULL,
    Gender VARCHAR(1) CHECK (Gender IN ('M', 'F')),
    Age INT,
    Grade VARCHAR(10),
    MathScore INT,
    ScienceScore INT,
    EnglishScore INT
);## 📸 Screenshots

### Database Schema
![Database Schema](/images/schema.png)

### Query Results
![Top Performers](/images/top_performers.png)
![Gender Analysis](/images/gender_analysis.png)

 License

MIT License

Copyright (c) 2025 Shoaib Asim

Permission is hereby granted...

 Author

Shoaib Asim
- 📧 Email: shoaibasim789@gmail.com  
- 💼 LinkedIn: [linkedin.com/in/yourprofile] 
(https://www.linkedin.com/in/shoaib-asim-82112927b)
