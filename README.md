# 5.1 Student Grades- racker



#### Objective:
In this assignment, students will learn how to work with Python dictionaries. They will practice creating, updating, and accessing dictionary data. The goal is to build a program that tracks student grades and performs various operations on them.

#### Instructions:
You will write a Python program to manage student grades using dictionaries. Follow the tasks below to complete the assignment.

---

### Part 1: Create a Dictionary

1. **Create an empty dictionary** called `student_grades`.
2. Add the following student names and their corresponding grades (on a 100-point scale) to the dictionary:
   - John Doe: 85
   - Jane Smith: 92
   - Emily Davis: 78
   - Michael Brown: 88

---

### Part 2: Access and Update Dictionary Data

1. **Print** the grade for "Jane Smith" from the dictionary.
2. **Update** the grade for "Emily Davis" to 82 (she completed some extra credit work).
3. **Add a new student** to the dictionary, "Olivia Wilson," with a grade of 91.

---

### Part 3: Dictionary Operations

Write a function for each of the following tasks:

1. **Display All Grades:**
   Write a function `print_all_grades(student_grades)` that takes in the dictionary and prints out each student's name and grade in the format:
   ```
   Name: Grade
   ```

2. **Calculate Average Grade:**
   Write a function `calculate_average(student_grades)` that takes in the dictionary and returns the average grade for all the students.

3. **Find Highest Grade:**
   Write a function `highest_grade(student_grades)` that returns the name of the student with the highest grade.

4. **Remove a Student:**
   Write a function `remove_student(student_grades, student_name)` that takes the dictionary and a student’s name as arguments, removes that student from the dictionary, and prints a message confirming their removal.

---

### Part 4: Testing Your Functions

1. After implementing the functions, test each of them:
   - Call `print_all_grades(student_grades)` to display all the students and their grades.
   - Call `calculate_average(student_grades)` to get the average grade and print it.
   - Call `highest_grade(student_grades)` to find and print the student with the highest grade.
   - Call `remove_student(student_grades, "Michael Brown")` to remove "Michael Brown" from the dictionary.
   - Call `print_all_grades(student_grades)` again to ensure the student has been removed.

---

### Part 5: Challenge 

1. **Find Students Above a Certain Grade:**
   Write a function `students_above_grade(student_grades, min_grade)` that takes the dictionary and a minimum grade as arguments, then prints the names of all students who have a grade higher than `min_grade`.

2. **Sort Students by Grades:**
   Write a function `sort_students_by_grades(student_grades)` that sorts the students in descending order of their grades and returns the sorted list.

---

### Example Output:

```
All students and their grades:
John Doe: 85
Jane Smith: 92
Emily Davis: 82
Michael Brown: 88
Olivia Wilson: 91

Average grade: 87.6
Highest grade: Jane Smith

Removing Michael Brown from the list...
Updated list of students:
John Doe: 85
Jane Smith: 92
Emily Davis: 82
Olivia Wilson: 91
```

