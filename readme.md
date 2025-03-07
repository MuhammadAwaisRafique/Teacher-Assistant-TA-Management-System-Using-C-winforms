TA and Demonstrator Management System

Overview

The TA and Demonstrator Management System is a comprehensive application built using C# WinForms and MS SQL Server to streamline the management of Teaching Assistants (TAs) and Lab Demonstrators (LDs). This system provides features for student applications, role-based dashboards, feedback management, and schedule handling.

Features

1. Student Applications

Students can apply to become a TA or Lab Demonstrator.

Application data is stored securely in the database for review.

2. CRUD Operations for TA/LD

TAs and Lab Demonstrators can manage their demo schedules.

Users can edit profiles, update availability, and add notes.

TAs and LDs can provide feedback to students.

3. Feedback Interaction

Students can view feedback given by TAs and Lab Demonstrators.

A structured interaction system ensures clear communication between students and staff.

4. Role-Specific Dashboards

TA Dashboard: View assigned tasks, schedules, and manage feedback.

Lab Demonstrator Dashboard: Manage demonstrations, student interactions, and schedules.

Student Dashboard: Apply for positions and respond to feedback.

Technologies Used

C# (WinForms) for frontend development.

MS SQL Server for database management.

SQL Server Management Studio (SSMS) for query execution and database handling.

Entity Framework (if applicable) for ORM.

Installation Guide

Prerequisites

Visual Studio (with .NET Framework support)

SQL Server and SQL Server Management Studio (SSMS)

.NET Framework (if required by your project setup)

Steps

Clone the repository:

git clone 

Open the solution in Visual Studio.

Configure the database connection string in app.config or relevant configuration file.

Run SQL scripts (if provided) to set up the database schema.

Build and run the project.

Usage

Login/Register as a Student, TA, or Lab Demonstrator.

Students can apply for positions and respond to feedback.

TAs/LDs can manage schedules and interact with students.

Admins (if applicable) can oversee and manage the system.

Future Enhancements

Implementing an Admin Dashboard for centralized control.

Adding email notifications for application updates.

Enhancing UI/UX with modern design elements.

Contact

For queries or contributions, please reach out at: [Your Email]

Developed by Muhammad Awais Rafique | May 2024

