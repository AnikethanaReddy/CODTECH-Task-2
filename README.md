_**Student Management System - Overview**_
This project implements a basic Student Management System using the C programming language. The system is designed to handle student registration, maintain student records, and calculate grades. It allows adding, editing, and deleting student information. Below is an overview of the main features and components of the system:

Features:
Add Student:

Allows the user to add a new student by providing the student's ID, name, and marks for five subjects.
Automatically calculates the average of the student's marks.
Edit Student:

Enables the user to update an existing student's name and marks by searching for the student using their ID.
Recalculates the average after editing the marks.
Delete Student:

Provides the option to delete a student's record from the system using their ID.
View All Students:

Displays all student records, including ID, name, marks for all subjects, and average grade.
Ensures users can easily review the current student database.
Exit:

Terminates the program gracefully.
Code Structure:
Data Structure:

The system uses a struct Student to store each student's information. This structure includes fields for the student's ID, name, marks for five subjects, and their average grade.
Array of Students:

The system maintains an array of struct Student to store multiple students. The maximum number of students that can be added is defined by the constant MAX_STUDENTS (default is 100).
Functions:

addStudent(): Handles the addition of new students by prompting the user for student details and calculating the average grade.
editStudent(): Allows editing of a student's details by searching for the student using their ID and updating the relevant information.
deleteStudent(): Deletes a student's record from the array by shifting the remaining records.
viewStudents(): Displays all the students currently stored in the system.
Main Menu:

The program runs a loop that presents a menu to the user, allowing them to choose between the different operations (Add, Edit, Delete, View, Exit).
The loop continues until the user selects the "Exit" option.
Example Workflow:
Adding a Student:

The user selects "Add Student" from the menu.
The system prompts for the student's ID, name, and marks in five subjects.
After inputting the data, the system calculates the student's average and stores the information.
Editing a Student:

The user selects "Edit Student" from the menu.
The system prompts for the student's ID and allows the user to update the student's name and marks.
Deleting a Student:

The user selects "Delete Student" from the menu.
The system prompts for the student's ID and removes the record if it exists.
Viewing Students:

The user selects "View All Students" to display all stored student records.
