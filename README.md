# database-gui.csharp
A C# Windows Forms application for managing courses, users, assessments, and academic performance, powered by a SQL Server database. Includes full CRUD operations, messaging, role-based access, and analytics.

# Course Management System 🎓📚

This project is a full-featured **C# Windows Forms** application designed to manage courses, users, assessments, and academic records in an educational institution. It supports **SQL Server integration**, **role-based access**, and multiple communication and reporting features.

---

## 🧠 System Overview

A comprehensive platform for:
- 📋 Course administration
- 👩‍🎓 Student and instructor account handling
- 📝 Exams, quizzes, and assignments
- 💬 Messaging and announcements
- 📊 Performance analytics and reporting

---

## 🚀 Key Features

### 🔐 User Management
- Registration for **students and instructors**
- **Role-based access control**
- Secure account credential management

### 📘 Course Administration
- Course creation and categorization
- Semester-based course assignment
- Course browsing and enrollment

### 🧪 Academic Tools
- Add exercises, assignments, exams, quizzes
- Student submission and grading
- Performance tracking with analytics

### 📢 Communication
- In-app **announcements** (e.g., "exam posted")
- Messaging between instructors and students

### 📊 Reporting
- Enrollment statistics
- Unassigned courses detection
- Top-performing student insights

---

## 🗃️ Database Schema (SQL Server)

**Core Tables**
- `ACCOUNT` — Login credentials
- `USER` — Base user profile with role (student/instructor)
- `STUDENT`, `INSTRUCTOR` — Extended info

**Course Management**
- `CATEGORY` — Course type (e.g., Programming, SE)
- `COURSE` — Course data
- `STUDENT_ENROLL_IN_COURSE` — Enrollment records

**Assessment**
- `ASSESMENT` — All evaluations
- `SUBMISSION` — Student answers and uploads

**Communication**
- `MESSAGE` — Private messages
- `ANNOUNCEMENT` — Course-level notices

---

## 🛠️ Installation & Setup

### 🔧 Database
- Execute `scriptCMS.sql` in **SQL Server** to create the full schema (tables, relations, constraints)
- Populate `CATEGORY` with course types

### 💻 Application
```bash

👩‍🏫 Usage Guide
For Instructors
Create and manage courses

Add assessments

Post announcements

Communicate with students

Track student progress

For Students
Browse & enroll in courses

Submit assessments

Check grades

Message instructors

✅ Business Requirements Covered
🔐 Role-based secure access

🛠️ Full course management

🧮 Assessment workflows

📊 Performance dashboards

💬 Messaging and feedback

🧾 Technical Specs
Language: C# (.NET Framework / WinForms)

Database: Microsoft SQL Server

Frontend: Windows Forms GUI

Security: Role-based login & validations

Validation: CHECK constraints at DB level

📷 Screenshots (optional)
Add screenshots of the interface here (login form, course dashboard, assessment screen, etc.)

✍️ Author
Malak Ali
Data Science Student | Backend & Database Developer
