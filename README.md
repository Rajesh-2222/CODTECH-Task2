CODTECH IT (STUDENT GRADE TRACKER)

NAME : RAJESH M

COMPANY : CodTech IT Solutions

ID : CT08DS108

DOMAIN : PYTHON PROGRAMMING

DURATION : November 2024 - December 2024



 Project: Student Grade Tracker

 Objective:  Develop a Python program to track and manage student grades. This program will allow users to input grades for various subjects or assignments, calculate the average grade, and display the overall grade along with additional information (such as a letter grade or GPA).


Technologies Used: 

1. Python Programming Language:
   - Python will be used to develop the Student Grade Tracker due to its simplicity and rich set of features for data handling.  

2. Python Standard Library:
   - No external libraries are needed—this program can be built entirely using Python's standard functionalities.  

3. Integrated Development Environment (IDE):
   - Development and debugging can be performed in any modern IDE, such as:
     - PyCharm
     - Visual Studio Code
     - Jupyter Notebook
     - IDLE (Python's built-in IDE)
4. Data Structures:  
   - List: Used to store the grades entered by the user.  
   - Strings and Floats**: To handle inputs and computations (e.g., grades, averages, and letter grades).  

5. Input and Output (I/O):  
   - `input()`: Used for taking grades, menu options, and other user inputs.  
   - `print()`: For displaying results, menus, and error messages to the console.  

6. Control Flow:  
   - Conditional statements (`if-elif-else`) to validate input and execute the appropriate logic.  
   - Loops (`while` or `for`) to allow repeated actions, such as adding grades or calculating averages.  

7. Error Handling:  
     - `try-except` blocks for managing invalid input, such as:  
     - Non-numeric values when entering grades.  
     - Division by zero when calculating the average of no grades.  

8. Modular Design:  
   - Code will be organized into classes, methods, and reusable components for enhanced readability and maintainability.  

9. Formatting Tools:  
   - Built-in functions like `round()` or string formatting (`f-strings`) to present numerical results in a clean and user-friendly way (e.g., average grade to 2 decimal places).  

10. Optional External Libraries (for future enhancements):
    - Tabulate: For displaying grades in a table format.  
    - Matplotlib or Plotly: For visualizing grades or averages in a chart.  

11. Version Control:
    - Use of Git or any version control system for tracking code changes during development.


  Program Features :

1. Tracks Grades:  
   - Users can add multiple grades for different assignments or subjects.  

2. Average Calculation:  
   - Computes the average of all grades entered by the user.  

3. Letter Grade Conversion:  
   - Converts the average numeric grade into a standard letter grade (A, B, C, D, or F).  

4. View Grades:  
   - Displays a list of all grades entered during the session.  

5. Error Handling:  
   - Handles invalid numeric inputs and ensures grades are within the range of 0-100.  

6. User-Friendly Interface:  
   - Menu-driven interface with clear prompts and error messages.  



  Program Workflow:

1. Initialization:  
   - Create a `StudentGradeTracker` instance and initialize an empty grades list.  

2. Menu Options:
   - Add Grade: Allows users to input valid grades.  
   - Calculate Average: Displays the average of all grades entered.  
   - Display Letter Grade: Shows the letter grade corresponding to the average.  
   - Show Grades: Lists all grades entered by the user.  
   - Exit: Ends the program.  

3. Input Validation:
   - Ensures numeric input for grades and validates the range (0-100).  

4. Program Termination:
   - Exits the loop and terminates upon user selection of the "Exit" option.  


Sample Execution:

Welcome to the Student Grade Tracker!

Options:
1. Add a grade
2. Calculate average grade
3. Display letter grade
4. Show all grades
5. Exit
Enter your choice: 1
Enter a grade (0-100): 85
Grade 85.0 added successfully.

Options:
1. Add a grade
2. Calculate average grade
3. Display letter grade
4. Show all grades
5. Exit
Enter your choice: 1
Enter a grade (0-100): 92
Grade 92.0 added successfully.

Options:
1. Add a grade
2. Calculate average grade
3. Display letter grade
4. Show all grades
5. Exit
Enter your choice: 2
Average Grade: 88.50

Options:
1. Add a grade
2. Calculate average grade
3. Display letter grade
4. Show all grades
5. Exit
Enter your choice: 3
Letter Grade: B

Options:
1. Add a grade
2. Calculate average grade
3. Display letter grade
4. Show all grades
5. Exit
Enter your choice: 4
Grades entered: 85.0, 92.0

Options:
1. Add a grade
2. Calculate average grade
3. Display letter grade
4. Show all grades
5. Exit
Enter your choice: 5
Goodbye! Thank you for using the Student Grade Tracker!

Potential Enhancements:

1. Subject-Specific Grades:  
   - Allow users to categorize grades by subjects (e.g., Math, Science).  

2. Grade Removal:  
   - Enable users to delete grades from the list.  

3. Weighted Grades:  
   - Add support for weighted grades based on assignment type (e.g., exams, homework).  

4. Letter Grade Scale Customization:  
   - Let users define their own letter-grade thresholds.  

5. Session Summary:  
   - Display a summary report at the end, showing all grades, average, and letter grade.  

 

