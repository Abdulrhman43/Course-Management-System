# 🎓 Course Management System 📚

## 📌 Overview  
This project is a **Course Management System** desktop application developed using **C# (Windows Forms GUI)** and backed by a **Microsoft SQL Server** database.  
It allows users to:

- Register as students or instructors  
- Manage courses and assignments  
- Register students in courses and track their grades  
- Create and assign exams  
- Add lessons and course content  
- Communicate via chat between users  

The system is designed following **Object-Oriented Programming (OOP)** principles to ensure modularity and scalability.

---

## ✅ Features  
- ✅ User registration and profile updates  
- ✅ Add and edit courses by instructors  
- ✅ Assign exams to courses  
- ✅ Register students to courses with grade management  
- ✅ Add detailed exam questions, dates, and durations  
- ✅ Create classwork assignments linked to courses  
- ✅ Add lessons and content to courses  
- ✅ Real-time chat between users with message timestamps and sender/receiver info  

---

## 🧾 Functional Requirements Implemented  

| Functionality               | Description                                                                                      |
|----------------------------|--------------------------------------------------------------------------------------------------|
| Register a new user         | User details (name, role, email, password) saved in `Userr` table.                               |
| Update user profile         | Update email, password, or role in `Userr` table.                                               |
| Add/edit course (instructor)| Instructors create/update courses (title, description, year, semester).                         |
| Assign exam to course       | Exams created and linked to courses via `ExamId`.                                               |
| Register student in course  | Students linked to courses via `Register` table with grade tracking.                            |
| Add exam details            | Add exam questions, duration, and date in `Exam` table.                                        |
| Create classwork (assignment)| Assignments linked to courses via composite keys.                                             |
| Add lessons or content      | Add lessons tied to courses with content and dates.                                            |
| Chat between users          | Manage chat threads and messages with timestamps, sender/receiver info.                        |

---

## ⚙️ How It Works  
1️⃣ Users register and login as students or instructors.  
2️⃣ Instructors can create or update courses and assign exams or classwork.  
3️⃣ Students can register in courses and view their grades.  
4️⃣ Users can exchange messages via the chat system.  
5️⃣ The system tracks and stores all data in a **Microsoft SQL Server** database.  

---

## 🛠️ Technologies Used  
- **C# (Windows Forms)** – For GUI and application logic  
- **Microsoft SQL Server** – For relational database management  
- **Visual Studio** – Development environment  
- **Draw.io & PowerDesigner** – Database ERD design  
- **GitHub** – Source control and collaboration  
- **Microsoft Word** – Documentation  

---
