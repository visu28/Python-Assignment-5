# Python-Assignment-5
Python Program Documentation
Program 1: Student Grade Lookup System (file1.py)
Description
A simple console application to look up student grades from a predefined dictionary.

Features
Takes student name as input

Returns corresponding grade if found

Handles "not found" cases gracefully

Implementation
python
student_marks = {
    "Alice": 85,
    "Bob": 78,
    "Charlie": 92,
    "David": 88,
    "Eva": 95
}

student_name = input("Please enter the student's name: ")

if student_name in student_marks:
    print(f"{student_name}'s marks: {student_marks[student_name]}")
else:
    print("Student not found.")
Sample Usage
shell
Please enter the student's name: Charlie
Charlie's marks: 92
Program 2: List Operations Demonstrator (file2.py)
Description
Demonstrates basic list operations including slicing and reversal.

Features
Creates a numbered list

Extracts first five elements

Reverses the extracted elements

Displays all transformations

Implementation
python
numbers = list(range(1, 11))

original_list = numbers[0:11]
extracted_elements = numbers[:5]
reversed_elements = extracted_elements[::-1]

print("Original list:", original_list)
print("Extracted elements:", extracted_elements)
print("Reversed elements:", reversed_elements)
Sample Usage
shell
Original list: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Extracted elements: [1, 2, 3, 4, 5]
Reversed elements: [5, 4, 3, 2, 1]
System Requirements
Python 3.6+

No external dependencies
