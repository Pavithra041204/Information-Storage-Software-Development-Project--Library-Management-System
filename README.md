# 📚 Library Management System (Python + Streamlit)

## 🔧 Overview

This project is a **Library Management System** that enables both Admins and Students to manage library activities.  
Initially, the project was developed using **C++ with a console-based interface**, using arrays and functions.  
Now, it has been **upgraded to a web application** using **Python and Streamlit**, providing a graphical and more user-friendly interface.

---

## 🚀 Features

### 👨‍💻 Admin Panel
| Feature | Description |
|--------|-------------|
| ➕ Add Book | Add new books to the library. |
| ✏️ Edit Book | Modify book title or author details. |
| 📄 View Books | Displays all books and their availability status. |
| 👥 View Students | Shows student roll number, name, and balance. |

### 👩‍🎓 Student Panel
| Feature | Description |
|--------|-------------|
| 🆕 Create Account | Register with a minimum initial deposit amount. |
| 💵 Deposit Amount | Add funds to account balance. |
| 👀 View Balance | Displays balance and student information. |
| 📕 Issue Book | Allows issuing books if balance ≥ required amount. |

---

## 🛠️ Technology Used

| Component | Technology |
|----------|------------|
| Programming Language | **Python** (previous version was C++) |
| Framework / UI | **Streamlit** (web-based interface) |
| Data Handling | `st.session_state` (temporary in-memory storage) |
| IDE | VS Code / Any editor of choice |

> The earlier version used **arrays, functions, loops, conditional statements** in C++.  
> The upgraded version demonstrates **web UI, state management, and event-driven programming** in Streamlit.

---

## 🔄 Evolution of the Project

| Old Version (C++) | New Version (Streamlit + Python) |
|-------------------|----------------------------------|
| Console-based interaction | Browser-based UI with buttons, forms, tabs |
| Arrays for saving books and students | Uses `session_state` (later expandable to SQLite DB) |
| Manual input navigation | User-friendly UI with proper layout |
| Output shown as plain text | Output displayed as tables & UI components |

---

## 📁 Project Structure

