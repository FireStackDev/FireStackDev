# 📝 ExamSphere - Marksheet Management System

A comprehensive monolithic PHP system for managing exams, marksheets, and student results.
Supports Admin, Teacher, and Student portals with full CRUD operations and streamlined workflows.

---

## 🚀 Features

### Admin Portal

* ✅ Manage Papers, Streams, Exams, Students, Teachers, and Marksheets
* 🔓 Open/Close Enrolment
* 🎯 Assign Head Examiners
* 📝 Distribute Papers
* 🔒 Lock/Unlock Marks Upload
* 📤 Publish Marksheets

### Student Portal

* 🧑‍🎓 Register & Login
* 📝 Update Profile
* 📋 Enrol/Cancel Exam
* 🏆 Check Results

### Teacher Portal

* 🔑 Login
* 📝 Update Profile
* 📤 Upload Marks

---

## 📊 Exam Schema

1. **Create Papers**
2. **Create Streams** → Add papers to streams
3. **Create Examinations** → Add streams to exams

---

## 💻 Project Structure (Concise)

```
/exam-sphere
│   README.md
│   index.php
│   login.php
│   *.sql, *.php, *.css
│
├─ /admin
│   ├─ *.php, *.css, *.js

├─ /teacher
│   ├─ *.php, *.css, *.js

├─ /candidate
│   ├─ *.php, *.css, *.js

├─ /assets
│   ├─ *.png, *.jpg

├─ /include
│   ├─ connect.php, header.php

├─ /phpqrcode
│   ├─ *.php, /bindings, /cache, /tools

├─ /profile_img
│   ├─ /admin, /student, /teacher

├─ /qr_codes
│   ├─ *.png

└─ /side nav
    ├─ sidenav.php, sidenav.css
```

> **Tip:** Use `tree /F` in Windows CMD to display the full file and folder hierarchy.

---

## 🌟 Screenshots

![Admin Dashboard](https://via.placeholder.com/400x200?text=Admin+Dashboard)
![Student Portal](https://via.placeholder.com/400x200?text=Student+Portal)
![Teacher Portal](https://via.placeholder.com/400x200?text=Teacher+Portal)

---

## 📌 License

MIT License © 2025
