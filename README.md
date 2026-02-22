DBMS Lab 3 – Data Collection and Data Insertion

**Overview**

This project demonstrates real-world data collection and insertion in a relational database using SQL.
The database represents a college management system and includes information about departments, faculty members, courses, students, and enrollments.

College

B. P. Mandal College of Engineering, Madhepura, Bihar

**Objective**

- Understand how real data is collected from authentic sources.
- Insert structured data into relational database tables.
- Maintain relationships using primary keys and foreign keys.
- Verify inserted data using SQL queries.

**Database Tables**

The following tables are used in this project:

1. Department

Stores department information.

- Department ID
- Department Name
- Office Location / Block

2. Faculty

Contains details about faculty members.

- Faculty ID
- Faculty Name
- Designation
- Official Email
- Department ID

3. Course

Stores course information offered by departments.

- Course ID
- Course Name
- Credits
- Department ID
- Faculty ID

4. Student

Contains student records.

- Student ID
- Student Name
- Date of Birth
- Gender
- Contact Number
- Department ID

5. Enrollment

Represents the relationship between students and courses.

- Student ID
- Course ID
- Semester
- Grade

**Data Sources**

Data was collected from authentic academic references such as:

- College website
- Department pages
- Class timetable
- Academic syllabus
- Class records

Dummy contact numbers were used for privacy.

**Tasks Performed**

1. Created database tables in SQL.
2. Inserted records into all tables.
3. Added a minimum of 10 records for Student, Course, and Enrollment tables.
4. Maintained proper relationships using foreign keys.
5. Verified the data using SELECT queries.

**Verification Queries**

SELECT * FROM Department;
SELECT * FROM Faculty;
SELECT * FROM Course;
SELECT * FROM Student;
SELECT * FROM Enrollment;

**Learning Outcomes**

- Practical understanding of relational databases.
- Writing SQL INSERT statements.
- Managing relationships between tables.
- Basic database verification techniques.



Student – DBMS Laboratory
B. P. Mandal College of Engineering
