# 📒 Contact Book (Python + MySQL Project)

## 📝 Overview

This is a **command-line-based Contact Book** built using **Python** and **MySQL**. It allows users to **add**, **view**, **search**, and **delete** contacts from a MySQL database. This project is great for beginners learning **database integration with Python**.

---

## 💡 Features

* 📇 **Add New Contacts**
* 📃 **Display All Contacts**
* 🔍 **Search Contact by Name**
* 🗑️ **Delete Contact**
* 🖥️ **Simple CLI Menu Interface**

---

## 🛠️ Tech Stack

* **Language**: Python
* **Database**: MySQL
* **Connector**: `mysql-connector-python`
* **Environment**: CLI (Command Line Interface)

---

## 🧠 Concepts Practiced

* Python Functions
* Exception Handling
* SQL Operations: `INSERT`, `SELECT`, `DELETE`
* Database Connectivity using `mysql.connector`
* Command-Line Menus

---

## ⚙️ How to Run

### ✅ Prerequisites

* Python installed
* MySQL server running
* `mysql-connector-python` installed (`pip install mysql-connector-python`)
* MySQL database and table set up (see below)

### 🔧 MySQL Setup

```sql
CREATE DATABASE contact_book;

USE contact_book;

CREATE TABLE contacts (
    name VARCHAR(100),
    phone VARCHAR(20),
    email VARCHAR(100)
);
```

### ▶️ Run the Script

```bash
python contact_book.py
```

---

## 🧾 Sample Menu Output

```
===== Contact Book Menu =====
1. Add Contact
2. Display All Contacts
3. Search Contact
4. Delete Contact
5. Exit
```

---

## 📂 Project Structure

```
📁 Contact-Book-MySQL/
├── contact_book.py
└── README.md
```

---

## 📌 Future Enhancements

* Update contact feature
* Export contacts to CSV
* GUI version using Tkinter
* Login system for multiple users

---

## 🙋‍♀️ Author

**Ankita Wasekar**

> A passionate data enthusiast building real-world Python projects.

---

## 🧾  Output Image :Contact Book1
![image alt](https://github.com/Ankita-Wasekar/Contact-Book/blob/c6def65354cc66cac4e41e1582491c6229934c9d/contactbook%201%20output.png)

## 🧾  Output Image :Contact Book2
![image alt](https://github.com/Ankita-Wasekar/Contact-Book/blob/c6def65354cc66cac4e41e1582491c6229934c9d/Contact%20Book%202%20output.png)


