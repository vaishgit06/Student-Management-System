# Student Management System

A simple **console-based Student Management System developed using Java**. The project allows users to manage student records and perform basic CRUD operations such as adding, viewing, searching, updating, and deleting students.

The application also calculates the total marks, percentage, and grade of each student.

---

## 📌 Project Overview

Managing student records manually can be time-consuming and prone to errors. This project provides a simple computerized solution for maintaining student information.

The system stores student details such as:

* Student ID
* Student Name
* Course
* Java Marks
* DBMS Marks
* DSA Marks
* Total Marks
* Percentage
* Grade

The project is designed as a beginner-friendly Java application and demonstrates important concepts of **Object-Oriented Programming (OOP)** and Java collections.

---

## ✨ Features

The application provides the following features:

1. **Add Student**

   * Add a new student record.
   * Checks whether the Student ID already exists.
   * Validates marks between 0 and 100.

2. **Display All Students**

   * Displays all stored student records
   * Shows total marks, percentage and grade

3. **Search Student**

   * Search for a student using their Student ID

4. **Update Student**

   * Update student name.
   * Update course.
   * Update marks.

5. **Delete Student**

   * Delete a student record using Student ID.

6. **Grade Calculation**

   * Automatically calculates percentage and grade.

---

## 🛠️ Technologies Used

| Technology   | Purpose                   |
| ------------ | ------------------------- |
| Java         | Main programming language |
| ArrayList    | Store student records     |
| Scanner      | Take user input           |
| OOP          | Structure the application |
| Command Line | Application interface     |

---

## 📋 Prerequisites

Before running the project, make sure the following software is installed on your computer:

### 1. Java Development Kit (JDK)

You need **JDK 8 or later**.

You can check whether Java is installed by opening a terminal or command prompt and running:

```bash
java -version
```

Also check the Java compiler:

```bash
javac -version
```

If both commands return a Java version, Java is installed correctly.

---

### Step 2: Navigate to the Project Directory

```bash
cd student-management-system
```

---

### Step 3: Check the Project Files

The project should contain the Java source file:

```text
student-management-system/
│
├── README.md
└── StudentManagementSystem.java
```

Make sure `README.md` is located at the **root level of the repository**.

---

## ⚙️ Environment Setup

This project does not require any external libraries, frameworks, databases, API keys, or environment variables.

Only the Java Development Kit (JDK) is required.

Recommended environment:

```text
Operating System : Windows / Linux / macOS
Java             : JDK 8+
IDE              : VS Code / IntelliJ IDEA / Eclipse / NetBeans
```

---

## 📦 Dependency Installation

There are **no external dependencies** required for this project.

The project uses only standard Java classes:

```java
import java.util.ArrayList;
import java.util.Scanner;
```

Both classes are included in the standard Java library.

Therefore, no `npm install`, `pip install`, Maven dependency, or Gradle dependency is required.

---

## ▶️ Running the Project

### Method 1: Using Command Prompt / Terminal

Compile the Java program:

```bash
javac StudentManagementSystem.java
```

If compilation is successful, run the application:

```bash
java StudentManagementSystem
```

---

### Method 2: Using VS Code

1. Install **Visual Studio Code**.
2. Install the **Extension Pack for Java**.
3. Open the project folder in VS Code.
4. Open:

```text
StudentManagementSystem.java
```

5. Click the **Run** button above the `main()` method.
6. The application will start in the terminal.

---

### Method 3: Using IntelliJ IDEA

1. Open IntelliJ IDEA.
2. Select **Open Project**.
3. Select the project folder.
4. Open `StudentManagementSystem.java`.
5. Locate the `main()` method.
6. Click the green **Run ▶** button.
7. Use the console to interact with the application.

---

## 🖥️ Application Menu

When the application starts, the following menu is displayed:

```text
========================================
       STUDENT MANAGEMENT SYSTEM
========================================
1. Add Student
2. Display All Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit
========================================
Enter your choice:
```

---

## 🧪 Example Usage

### Add a Student

Select:

```text
1
```

Then enter:

```text
Enter Student ID: 101
Enter Student Name: Ayush Singh
Enter Course: B.Tech CSE
Enter Java Marks: 85
Enter DBMS Marks: 78
Enter DSA Marks: 90
```

Output:

```text
Student added successfully!
```

---

### Display Student

Select:

```text
2
```

Example output:

```text
----------------------------------------
Student ID  : 101
Name        : Ayush Singh
Course      : B.Tech CSE
Java Marks  : 85.0
DBMS Marks  : 78.0
DSA Marks   : 90.0
Total Marks : 253.0/300
Percentage  : 84.33%
Grade       : A
----------------------------------------
```

---

## 📊 Grading System

The application calculates the grade based on the student's percentage.

| Percentage | Grade |
| ---------: | :---: |
|     90–100 |   A+  |
|      80–89 |   A   |
|      70–79 |   B   |
|      60–69 |   C   |
|      50–59 |   D   |
|   Below 50 |   F   |

### Percentage Formula

```text
Percentage = Total Marks / 3
```

Since there are three subjects and each subject has a maximum of 100 marks, the maximum total is 300.

---

## 🧠 Java Concepts Demonstrated

This project demonstrates several fundamental Java concepts.

### Object-Oriented Programming

* Classes
* Objects
* Constructors
* Encapsulation
* Methods
* Getters and setters

### Java Programming

* Variables
* Data types
* Conditional statements
* Switch statements
* Loops
* Methods
* Scanner
* ArrayList

### Data Management

The project uses:

```java
ArrayList<Student>
```

to store multiple student objects dynamically.

---

## 🚫 Configuration

No configuration file is required.

The project does not require:

* Database credentials
* API keys
* Environment variables
* Cloud services
* External APIs

The student records are stored temporarily in memory using `ArrayList`.

**Note:** Data will be lost when the application is closed.

---

## ⚠️ Limitations

The current version is a basic console application.

Current limitations include:

* Data is not permanently stored.
* No login/authentication system.
* No graphical user interface.
* No database integration.
* Records are lost when the program terminates.

---

## 🚀 Future Improvements

The project can be extended in future versions by adding:

### Version 2 – File Handling

Store student records permanently using files.

### Version 3 – MySQL Database

Use **MySQL and JDBC** for permanent database storage.

### Version 4 – GUI

Create a graphical interface using:

* Java Swing
* JavaFX

### Version 5 – Authentication

Add:

* Admin login
* Student login
* Password management

### Version 6 – Advanced Features

Possible additions:

* Attendance management
* Subject management
* Semester-wise records
* Student ranking
* Report generation
* Search by name or course
* Export records to CSV/PDF

---

## 👨‍💻 Author

**Vaishnavi Singh Chauhan**

B.Tech Computer Science and Engineering


# Student-Management-System
The objective of this project is to develop a simple console-based application for managing student information.
