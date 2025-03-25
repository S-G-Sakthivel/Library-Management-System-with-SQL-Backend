# Library Management System 📚  

A simple **console-based Library Management System** with **SQL database connectivity**, allowing users to manage books efficiently.  

## Features 🚀  

✔️ Add new books to the library  
✔️ Borrow and return books  
✔️ Check book availability  
✔️ View all books  

## Setup Instructions 🛠️  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/S-G-Sakthivel/Library-Management-System-with-SQL-Backend.git
cd Library-Management-System-with-SQL-Backend
```

### 2️⃣ Configure the Database  

#### Create the Database  
```sql
CREATE DATABASE LibraryDB;
USE LibraryDB;
```

#### Create the Books Table  
```sql
CREATE TABLE books (
    book_id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    author VARCHAR(255) NOT NULL,
    available TINYINT(1) DEFAULT 1
);
```

### 3️⃣ Update Database Credentials  
- Open the **Java file** and update the **JDBC URL, username, and password** as per your MySQL setup.  

### 4️⃣ Compile and Run the Program  
```sh
javac LibraryManagement.java
java LibraryManagement
```

## Requirements 📌  
- **Java 8+**  
- **MySQL Database**  
- **JDBC Driver**  
