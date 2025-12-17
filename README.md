Student Grade Calculator
Python Mini Project – Week 2
________________________________________
1. Project Overview
Project Title
Student Grade Calculator using Python
Project Description
The Student Grade Calculator is a beginner-level Python program designed to calculate a student’s grade based on their marks. The program accepts user input, validates the data, assigns grades using conditional statements, and displays encouraging messages.
Project Goals and Objectives
•	To understand and apply if-elif-else statements
•	To use loops for repeated execution and validation
•	To implement functions for reusable code
•	To handle invalid input using basic error handling
•	To build confidence in writing structured Python programs
________________________________________
2. Setup Instructions
System Requirements
•	Operating System: Windows / macOS / Linux
•	Python Version: Python 3.x
•	Code Editor: VS Code / PyCharm / IDLE (any)
Installation Steps
1.	Download and install Python from the official website.
2.	Verify Python installation:
3.	python --version
4.	Download or clone the project repository.
5.	Navigate to the project folder.
6.	Run the program using:
7.	python grade_calculator.py
________________________________________
3. Code Structure
Project Folder Structure
Student-Grade-Calculator/
README.md
grade_calculator.py
test_cases.txt
screenshots/
    └── sc_example.png
File Description
•	grade_calculator.py – Main Python program
•	README.md – Project overview and instructions
•	test_cases.txt – Testing scenarios and expected results
•	screenshots/ – Visual proof of program execution
________________________________________
4. Visual Documentation
Screenshots Included
 
 
 
 

 

5. Technical Details
Programming Concepts Used
•	Conditional statements (if-elif-else)
•	Loops (while)
•	Functions
•	Exception handling (try-except)
•	User input and output
Algorithm Explanation
1.	Ask user to enter student name.
2.	Prompt user to enter marks.
3.	Validate marks (must be between 0 and 100).
4.	Repeat input request until valid marks are entered.
5.	Calculate grade based on grading rules.
6.	Display grade and encouraging message.
Grading Logic
Marks Range	Grade
90–100	A
80–89	B
70–79	C
60–69	D
0–59	F
Function Breakdown
•	calculate_grade(marks) – Determines grade and message
•	get_valid_marks() – Handles input validation
•	main() – Controls program execution
________________________________________
6. Testing Evidence
Test Cases
Test Case	Input Marks	Expected Output
1	30	Grade F
2	62	Grade D
3	99	Grade A
4	71	Grade C
5	102	Marks must be between 0 and 100.
6	-	Invalid input
7	-5	Marks must be between 0 and 100.
Validation Handling
•	Ensures marks are numeric
•	Prevents values below 0 or above 100
•	Displays clear error messages
________________________________________
7. Conclusion
This project successfully demonstrates the use of decision-making, loops, and functions in Python. It follows proper coding practices, includes validation, and provides a user-friendly experience. The project meets all quality standards and learning objectives for Week 2.


