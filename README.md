# StudentProjectApp



A simple **Windows Forms application** built using **C# and MySQL** that allows users to perform CRUD (Create, Read, Update, Delete) operations on student records.




---

## ⚙️ Features

- Add new students to the MySQL database
- Update student details
- Delete student records
- Load and display all student data in a DataGridView
- Clean UI built using Windows Forms (WinForms)

---

## 🛠️ Tech Stack

| Technology | Description           |
|------------|-----------------------|
| C#         | Programming Language  |
| .NET       | Windows Forms App     |
| MySQL      | Database              |
| Visual Studio | IDE for development |

---

## 🚀 How to Run

1. **Clone the repo** or download the ZIP
2. Open the project in **Visual Studio**
3. Ensure **MySQL server** is running
4. Update your database connection string in `Form1.cs`:
   ```csharp
   string connectionString = "server=localhost;user id=root;password=;database=studentdb";



CREATE DATABASE studentdb;

CREATE TABLE students (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    age INT,
    course VARCHAR(100)
);

