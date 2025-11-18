# Student Marks Analysis

This project processes students' marks from a CSV file, calculates total, percentage, grade, and generates visual reports.

## Features

* Reads data from `students_marks.csv`
* Calculates:

  * Total marks
  * Percentage
  * Grade based on performance
  * Highest, lowest, and average percentage
  * Number of failing students (<60%)
  * Top-performing student
* Exports processed results to `marks_calculation.csv`
* Generates:

  * Bar chart of student percentages
  * Pie chart of grade distribution

## Grading Logic

| Percentage | Grade |
| ---------- | ----- |
| >= 90      | A+    |
| >= 80      | A     |
| >= 70      | B     |
| >= 60      | C     |
| < 60       | D     |

## Requirements

Make sure you have the following libraries installed:

```bash
pip install pandas matplotlib
```

## How to Run

1. Place `students_marks.csv` in the project directory.
2. Run the script:


```

3. The program will:

   * Print statistics in the terminal
   * Generate `marks_calculation.csv`
   * Save the bar chart as `report.png`
   * Display both plots

## Output Files

* **marks_calculation.csv** – Processed marks with total, percentage, and grade
* **report.png** – Bar chart of student performance

## Notes

* Ensure the CSV has the following columns: `Name`, `Math`, `Science`, `English`
* Modify the grading logic if needed for your project
