# Student Management System

A simple **Student Management System** developed using Java. This project is a console-based application that allows users to manage student records easily.

## Features

* Add a new student
* View all students
* Search for a student by ID
* Update student information
* Delete a student
* Exit the application
* Prevent duplicate student IDs

## Technologies Used

* Java
* Java Collections Framework
* ArrayList
* Scanner
* Object-Oriented Programming (OOP)

## Project Structure

```text
student-management-system-java/
│
├── src/
│   └── StudentManagementSystem.java
│
├── README.md
└── .gitignore
```

## Student Details

Each student record contains:

* Student ID
* Student Name
* Age
* Course

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/student-management-system-java.git
```

### 2. Open the project

Open the project in an IDE such as:

* IntelliJ IDEA
* Eclipse
* NetBeans
* VS Code

### 3. Compile the program

Navigate to the `src` directory and run:

```bash
javac StudentManagementSystem.java
```

### 4. Run the program

```bash
java StudentManagementSystem
```

## Menu

```text
==============================
   STUDENT MANAGEMENT SYSTEM
==============================
1. Add Student
2. View Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit
==============================
Enter your choice:
```

## Example

```text
Enter your choice: 1

Enter Student ID: 101
Enter Student Name: Rahul
Enter Age: 20
Enter Course: Computer Science

Student added successfully!
```

Viewing the record:

```text
===== Student Records =====
ID     : 101
Name   : Rahul
Age    : 20
Course : Computer Science
-------------------------
```

## Concepts Used

This project demonstrates important Java concepts:

* Classes and Objects
* Encapsulation
* Constructors
* Methods
* ArrayList
* Loops
* Conditional statements
* Switch statements
* User input using Scanner
* Basic CRUD operations

## Future Improvements

The project can be enhanced by adding:

* MySQL database connectivity
* Java Swing or JavaFX GUI
* Student attendance
* Marks and grades
* Login and authentication
* Export student records to CSV/PDF
* Spring Boot REST API

## License

This project is created for educational purposes.
