
## ITI Examination System Database
Welcome to the ITI Examination System Database repository! This project aims to simulate the Information Technology Institute (ITI) Examination System using Microsoft SQL Server. It includes various entities such as exams, instructors, students, courses, branches, intakes, tracks, and question pools, all designed to effectively serve the institution's needs.

Features
Branch Management: The institution operates multiple branches, each overseen by one or more managers. Each branch conducts multiple intakes throughout the year, offering various tracks.

Exam Creation: Instructors can create exams for their courses, either by specifying the number of questions and grades or manually selecting questions from the question pool. The system ensures randomness and relevancy of questions.

Student Participation: Students can submit their answers for specific exams. The system grades the answers and determines whether the student has passed the test.

Training Manager Administration: Training managers have administrative capabilities over the branches they manage, including the management of tracks and intakes with different permissions.

## SQL Server Objects Used
Stored Procedures: Implement business logic and data manipulation operations.
Views: Present data in a readable format and facilitate data retrieval.
Triggers: Automatically execute actions in response to database events, ensuring data integrity.
Indexes: Optimize query performance by speeding up data retrieval operations.
Security Measures
Access Control: Four user accounts with different levels of accessibility and permissions are created to enhance database security.
Data Validation: Extensive validation is implemented for user inputs in each procedure to ensure data integrity and prevent unauthorized access or manipulation.
Backup Strategy: Full backups of database objects and data occur twice daily to prevent data loss.
File Groups: Organize database files into logical groups for improved manageability and performance
