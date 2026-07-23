# Student Marks Analyzer

A simple Python console application that stores students' marks, determines pass/fail status, and displays summary statistics.

## Features

- Add multiple students
- Store names and marks
- Automatically determine Pass/Fail
- Calculate:
  - Average Marks
  - Highest Marks
  - Lowest Marks

## Technologies Used

- Python 3

## How to Run

1. Clone the repository

```bash
git clone https://github.com/SaadDScientist/student-marks-analyzer.git
```

2. Navigate to the folder

```bash
cd student-marks-analyzer
```

3. Run

```bash
python student_marks_analyzer.py
```

## Example

```
Enter Student's Name:  Saad
Enter Student's Marks:  80
Do you want to enter another student's marks? (y/n):  y
Enter Student's Name:  Ali
Enter Student's Marks:  60
Do you want to enter another student's marks? (y/n):  y
Enter Student's Name:  Muhammad
Enter Student's Marks:  59
Do you want to enter another student's marks? (y/n):  n
Name: Saad, Marks: 80, Status: Pass
Name: Ali, Marks: 60, Status: Pass
Name: Muhammad, Marks: 59, Status: Fail

Overall Statistics
Average Marks : 66.33
Highest Marks : 80
Lowest Marks  : 59
```

## Future Improvements

- Save records to CSV
- Save records to Excel
- Add multiple subjects
- Add grade calculation
- GUI version using Tkinter
