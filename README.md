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

![WhatsApp Image 2025-05-18 at 18 51 40_4cbbd860](https://github.com/user-attachments/assets/12995870-dc99-4048-bce8-67afedc63c11)
![WhatsApp Image 2025-05-18 at 18 51 39_2d9efc33](https://github.com/user-attachments/assets/8b3e773b-2bc1-4bac-9925-530aaec1d8bc)
![WhatsApp Image 2025-05-18 at 18 51 41_9f146420](https://github.com/user-attachments/assets/d2d6d8fd-08c4-4507-8a21-1eb998f0ef34)
![WhatsApp Image 2025-05-18 at 18 51 43_041f6069](https://github.com/user-attachments/assets/87db6d47-7375-454c-8b26-50894be646e4)
![WhatsApp Image 2025-05-18 at 18 51 42_0d4df6cf](https://github.com/user-attachments/assets/8a4387fa-791b-4fdf-b76b-eb2b1299b389)
![WhatsApp Image 2025-05-18 at 18 51 45_a18ed254](https://github.com/user-attachments/assets/b287e782-ab65-46ab-a229-9870018c6271)
![WhatsApp Image 2025-05-18 at 18 51 41_3244c08c](https://github.com/user-attachments/assets/ac810b30-806a-41d8-8974-70d318795267)
![WhatsApp Image 2025-05-18 at 18 52 48_911c0a3c](https://github.com/user-attachments/assets/0bbd07f2-3455-4aa6-9422-6d725c1d0045)
![WhatsApp Image 2025-05-18 at 18 51 44_79c9680f](https://github.com/user-attachments/assets/cee92397-d465-49ce-bcaf-d516accc0190)
![WhatsApp Image 2025-05-18 at 18 51 44_758ca0a2](https://github.com/user-attachments/assets/51e0bcee-8963-4a59-8cce-8c23681dbbf0)




✍️ Author
Malak Ali
Data Science Student 
