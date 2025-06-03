# Python-Assignment-5
# Python Program Documentation

## Program 1: Student Grade Lookup System (file1.py)

### Overview
A console-based application that allows users to query student grades from a predefined database.

### Technical Specifications
- **Input:** Student name (string)
- **Output:** Corresponding grade or "not found" message
- **Data Structure:** Dictionary (key-value pairs)
- **Error Handling:** Basic existence check

### Code Implementation
```python
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

Usage Example
Please enter the student's name: Charlie
Charlie's marks: 92





Program 2: List Operations Demonstrator (file2.py)
Overview
A demonstration program showcasing fundamental list operations including slicing and reversal techniques.

Technical Specifications
Input: None (uses predefined data)

Output: Three formatted list displays:

Original number list

First five elements

Reversed subset

Data Structures:

List (sequential container)

Sliced sublists

Operations:

List generation

Complete slicing

Partial extraction

Sequence reversal

Code Implementation
python
numbers = list(range(1, 11))

original_list = numbers[0:11]
extracted_elements = numbers[:5]
reversed_elements = extracted_elements[::-1]

print("Original list:", original_list)
print("Extracted elements:", extracted_elements)
print("Reversed elements:", reversed_elements)
Usage Example
Original list: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Extracted elements: [1, 2, 3, 4, 5]
Reversed elements: [5, 4, 3, 2, 1]
Key Features
Demonstrates Python's slice notation

Shows forward and reverse indexing

Illustrates list creation from ranges

Outputs multiple transformation stages

Enhancement Notes
Could be extended with user-defined range input

Potential to add more transformation operations

May include graphical representation of list operations

This maintains the same formal documentation style as Program 1, with:

Clear section headers

Detailed technical specifications

Complete code block

Example output

Additional relevant sections

Consistent formatting throughout
