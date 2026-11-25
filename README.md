# STUDENT ATTENDANCE ANALYZER

**Batch:** 25

**Member 1:** Prachi  
**Member 2:** Devesh  
**Member 3:** Sukhpreet  

## Objectives and Features

- Accept attendance details for multiple students.
- Store the name and attendance record of each student.
- Calculate the attendance percentage of each student.
- Identify whether a student has sufficient or low attendance based on the minimum required percentage.
- Display student-wise attendance details.
- Display a class attendance report including the student with the highest attendance and the class average attendance.

## C Programming Concepts Used

1. Variables and Data Types
2. Structures
3. Arrays
4. Strings
5. Functions
6. Loops
7. Conditional Statements
8. Switch Case
9. Operators
10. Input/Output
11. Input Validation
12. Nested Loops

## Instructions to Compile and Execute the Program

1. Save the C source code as `student_attendance_analyzer.c`.
2. Open the file in a C compiler/IDE such as VS Code, Code::Blocks, Dev-C++, or GCC.
3. Compile the program to check for errors.
4. If using GCC, compile using:

`gcc student_attendance_analyzer.c -o student_attendance_analyzer`

5. Run the compiled program:

`./student_attendance_analyzer`

6. Enter the number of students when prompted.
7. Use the menu options to:
   - Enter student details and attendance
   - Display student attendance
   - Display the class attendance report
   - Exit the program

## Expected Output

Student-wise attendance summary and class attendance report, including attendance percentage, attendance status, student with the highest attendance, and class average attendance.

## Sample Output

```text
===== STUDENT ATTENDANCE ANALYZER =====

Enter number of students (1-10): 2

===== MENU =====
1. Enter Student Details
2. Display Student Attendance
3. Display Class Report
4. Exit

Enter your choice: 1

Enter name of student 1: Prachi
Enter total number of classes: 100
Enter number of classes attended: 85

Enter name of student 2: Devesh
Enter total number of classes: 100
Enter number of classes attended: 70

Student data entered successfully!

===== MENU =====
1. Enter Student Details
2. Display Student Attendance
3. Display Class Report
4. Exit

Enter your choice: 2

===== STUDENT ATTENDANCE =====

Name: Prachi
Classes Attended: 85 / 100
Attendance Percentage: 85.00%
STATUS = SUFFICIENT ATTENDANCE

Name: Devesh
Classes Attended: 70 / 100
Attendance Percentage: 70.00%
STATUS = LOW ATTENDANCE

===== MENU =====
1. Enter Student Details
2. Display Student Attendance
3. Display Class Report
4. Exit

Enter your choice: 3

===== CLASS REPORT =====

Highest Attendance: Prachi
Highest Attendance Percentage: 85.00%
Class Average Attendance: 77.50%

===== MENU =====
1. Enter Student Details
2. Display Student Attendance
3. Display Class Report
4. Exit

Enter your choice: 4

Exiting program..
```
