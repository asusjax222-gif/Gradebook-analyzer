## Project Overview

This is a mini project for the course "Programming for Problem Solving using Python." The GradeBook Analyzer is a Python-based tool that allows teachers to input student names and marks manually, compute statistical analyses (average, median, min, max), assign letter grades, and generate reports on pass/fail status. It provides a simple, automated way to analyze student performance without relying on spreadsheets or manual calculations.

## Learning Objectives

By completing this project, you will:
- Input and store student data using lists and dictionaries.
- Implement core statistical functions (mean, median, min, max).
- Apply control statements to assign letter grades.
- Use list comprehensions to separate pass and fail students.
- Develop modular code using functions and loops.
- Format results in a tabular form using f-strings.

## Features

- **Manual Data Entry**: Input the number of students and their names and marks.
- **Statistical Analysis**: Calculate and display average, median, minimum, and maximum scores.
- **Grade Assignment**: Assign letter grades (A, B, C, D, F) based on marks.
- **Grade Distribution**: Count students in each grade category.
- **Pass/Fail Filter**: Separate students into passed (marks >= 40) and failed lists using list comprehensions.
- **Formatted Output**: Display results in a neat table format.
- **Interactive Menu**: Loop to allow re-running analysis or exiting.

## Requirements

- Python 3.x (tested on Python 3.8+)
- No external libraries required (uses built-in Python features)

## Installation and Setup

1. Clone or download the project folder `gradebook_analyzer/`.
2. Ensure you have Python installed on your system.
3. Run the script `gradebook.py` from the command line or an IDE.

## Usage

1. Execute the script: `python gradebook.py`
2. Follow the prompts:
   - Enter the number of students.
   - For each student, enter their name and marks (0-100).
3. The script will compute and display:
   - Statistical summaries (average, median, min, max).
   - Grade assignments and distribution.
   - Pass/fail lists.
   - A formatted table of results.
4. Choose to re-run the analysis or exit via the menu.

### Example Output

```
Welcome to the GradeBook Analyzer!

How many students are in the class? 3

Enter name for student 1: Alice
Enter marks for Ram: 78

Enter name for student 2: Bob
Enter marks for Shyam: 92

Enter name for student 3: Carol
Enter marks for Luffy: 56

Statistical Analysis:
Average: 75.33
Median: 78.0
Max Score: 92 (Bob)
Min Score: 56 (Carol)

Grade Distribution:
A: 1
B: 0
C: 1
D: 0
F: 1

Passed Students (2): ['Alice', 'Bob']
Failed Students (1): ['Carol']

Results Table:
Name       Marks     Grade
--------------------------
Ram      78         C
Shyam    92         A
Luffy    56         F

Do you want to run the analysis again? (y/n): n
Sayonara(bye bye)!
```

## File Structure

- `gradebook.py`: Main script containing all functionality.
- `README.md`: This file, providing project documentation.

## Testing

- Test with at least 5 students to ensure all features work correctly.
- Verify edge cases: e.g., all passing, all failing, single student, invalid inputs (though basic input validation is assumed).

## Author

Name:- "Jayesh Shrivastava"
Date : 6/11/25
Subject : Programming for Problem Solving using Python
Course: Btech cse data science .......!!!






Output ss:-


![Output screen shot](<Screenshot 2025-11-06 191547.png>).







