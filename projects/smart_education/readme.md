# 📚 SmartEducationProject

SmartEducationProject is a modern educational platform designed to provide secure, scalable, and intelligent solutions for learning environments.  
It focuses on **advanced authentication**, **role-based access control**, and **future AI-powered features**.

---

## 🚀 Project Overview

This project serves as the backbone for a smart education system, enabling:
- Secure authentication via OTP & JWT token system.
- Role-based access (Students, Teachers, Admins, Officials, Superusers).
- Private media file handling via authenticated API endpoints.
- Advanced security features including CSRF protection, token rotation, and token blacklisting.

Built with:
- **Backend**: Django + Django Rest Framework
- **Database**: PostgreSQL (recommended) / MySQL (supported)
- **Deployment**: Configurable for local and cloud environments.

---

## 🛠 Features

- **Authentication & Security**
  - OTP-based login.
  - JWT with access & refresh tokens.
  - Token rotation & blacklisting.
  - CSRF protection.
  - Device logging (planned).
  
- **Role Management**
  - Superusers identified by `username`.
  - Regular users identified by `user_id` (UUID primary key).
  - Separate model handling for Teachers, Students, and Officials.

- **Media Privacy**
  - All media files stored in private directories.
  - Served securely via authenticated API endpoints.

- **Scalable Structure**
  - Modular app design for easier feature expansion.
  - Suitable for large-scale deployments.

---

## 🌿 Branch Strategy

This repository uses a **two-branch workflow**:

| Branch       | Purpose                                 |
|--------------|-----------------------------------------|
| `main`       | **Production-ready** code. Stable, tested, and deployable. |
| `development`| Base branch for **development & testing**. All new features and bug fixes branch off from here. |

### Branching Rules
- Always branch **from `development`** for new features or bug fixes.
- Pull requests should target **`development`**, not `main`.
- `main` only receives merged changes after full testing in `development`.

---

## 📂 Project Structure (Backend)
```
SmartEducationProject/
├── authentication/     # Auth app (OTP, JWT, permissions)
├── official/           # official app (official purpose)
├── media/              # Private media storage
├── smarteducation/     # project config
├── templates/          # templates
├── db.sqlite3          # sqlite test database
├── manage.py           # Django CLI
```

---

## 🧑‍💻 Getting Started

### Prerequisites
- Python 3.10+
- PostgreSQL or MySQL
- pipenv or virtualenv (recommended)