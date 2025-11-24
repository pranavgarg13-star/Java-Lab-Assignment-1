# Java-Assignment
By : Pranav Garg , Roll No. : 2401010034
Student Record Management System

This is a simple menu-driven Java application that stores student details, calculates grades, and displays all student records.
The program demonstrates inheritance, constructors, array lists, and basic validation in Java.

## Features
- Add new student details
- Uses Person → Student inheritance
- Input validation for marks (0–100)
- Automatic grade calculation
 a. A → 90 and above
 b. B → 75–89
 c. C → 60–74
 d. D → below 60
- Display all stored student records
- Menu-driven console interface using switch
- Uses ArrayList to store multiple student objects

## Classes Included
1. Person (Parent Class)

  - Stores basic attribute: name

2. Student (Child Class)

  - Inherits from Person
  - Attributes: roll number, course, marks, grade
  - Contains:
     - Default & parameterized constructor
     - Input method
     - Grade calculation
     - Display method

3. StudentRecordSystem (Main Class)
  - Runs menu
  - Stores students in an ArrayList
  - Allows adding & viewing student records

## How to Run

1. Compile the code : javac StudentRecordSystem.java


2. Run the program : java StudentRecordSystem

## Sample Interaction
===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice: 1


Enter Roll No: 101

Enter Name: Rohan

Enter Course: BCA

Enter Marks (0-100): 85

Student added successfully!


===== Student Record Menu =====
Enter your choice: 2

Roll No: 101

Name: Rohan

Course: BCA

Marks: 85.0

Grade: B
-----------------------------
