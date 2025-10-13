# 📝 ExamSphere - Marksheet Management System

A comprehensive system for managing exams, marksheets, and student results.
Supports Admin, Teacher, and Student portals with full CRUD operations and streamlined workflows.

---

## 🚀 Features

### Admin Portal

* ✅ CRUD operations for Paper, Stream, Exam, Student, Teacher, and Marksheet
* 🔓 Open/Close Enrolment
* 🎯 Assign Head Examiners
* 📝 Distribute Papers
* 🔒 Lock/Unlock Marks Upload
* 📤 Publish Marksheets

### Student Portal

* 🧑‍🎓 Student Registration
* 🔑 Login
* 📝 Profile Update
* 📋 Enrol/Cancel Enrolment in Exams
* 🏆 Check Results

### Teacher Portal

* 🔑 Login
* 📝 Profile Update
* 📤 Upload Marks

---

## 📊 Exam Schema

1. **Create Papers**
2. **Create Streams** → Add papers to the stream
3. **Create Examination** → Add streams to the examination

---

## 💻 Project Structure

```
/exam-sphere
│
├─ /admin
├─ /teacher
├─ /student
├─ /papers
├─ /streams
└─ /marksheets
```

---

## ⚡ Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/examsphere.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Configure the database and `.env` file.

4. Run the application:

```bash
python manage.py runserver
```

---

## 🌟 Screenshots

![Admin Dashboard](https://via.placeholder.com/400x200?text=Admin+Dashboard)
![Student Portal](https://via.placeholder.com/400x200?text=Student+Portal)
![Teacher Portal](https://via.placeholder.com/400x200?text=Teacher+Portal)

---

## 📌 License

MIT License © 2025
