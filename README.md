# University Management System

## Overview

University Management System is a comprehensive desktop application developed in Java using Object-Oriented Programming (OOP) principles and Java Swing GUI components. The system is designed to simplify university administration tasks such as student registration, course management, major management, academic record tracking, and grade calculation.

The project follows a layered architecture to ensure maintainability, scalability, and clean code organization.

## Features

### Student Management

* Add new students
* Search students by ID or name
* Delete students
* Sort students by major
* View student academic information
* GPA calculation

### Course Management

* Add courses
* Manage course information
* Assign courses to specific majors
* Remove courses safely

### Major Management

* Create new majors
* Delete existing majors
* Real-time updates across the system

### Grade Management

* Store student grades
* Automatic GPA calculation
* Academic performance tracking

### User Authentication

* Secure login screen
* Administrator access control

## Advanced Features

### Smart Deletion

The system automatically removes related dependencies when deleting records, ensuring data consistency.

### Modern User Interface

* Java Swing GUI
* Nimbus Look & Feel
* Consistent styling
* User-friendly navigation

### Arabic Data Support

Supports realistic Arabic names and academic records.

### Real-Time Data Management

All operations are reflected immediately throughout the application.

## Project Architecture

The project follows a three-layer architecture:

### Models Layer

Contains core entities:

* Person
* Student
* Course

### Data Layer

Contains:

* DataStore
* Data management operations
* In-memory database functionality

### UI Layer

Contains:

* LoginForm
* MainDashboard
* RegistrationDashboard
* StudentManager
* CourseManager

## OOP Concepts Implemented

### Inheritance

Student class extends the abstract Person class.

### Encapsulation

Private attributes with getters and setters.

### Abstraction

Abstract Person class defines common behavior.

### Polymorphism

Object-oriented design allows flexible extension and maintenance.

## Technologies Used

* Java
* Java Swing
* Object-Oriented Programming (OOP)
* Collections Framework
* In-Memory Data Storage

## Default Login

Username:
admin

Password:
admin

## Project Structure

```text
UniversityManagementSystem
│
├── Main.java
├── models
│   ├── Person.java
│   ├── Student.java
│   └── Course.java
│
├── data
│   └── DataStore.java
│
└── ui
    ├── LoginForm.java
    ├── MainDashboard.java
    ├── RegistrationDashboard.java
    ├── StudentManager.java
    └── CourseManager.java
```

## Future Improvements

* Database integration (MySQL/PostgreSQL)
* Student enrollment system
* Attendance tracking
* Role-based authentication
* Report generation (PDF/Excel)
* Web-based version
* REST API integration

## Educational Purpose

This project was developed as an academic project to demonstrate advanced Java programming concepts, GUI development, data management, and Object-Oriented Design principles.

## Author

Developed using Java and Object-Oriented Programming principles for educational and university management purposes.
