# Student Marks Analysis Project

## Project Overview
This project analyzes student marks across five subjects: **Math, Science, English, History, and Computer**. It calculates total and average scores, identifies top performers, analyzes subject-wise averages, and visualizes the results using various plots.

## Data
The input data should be a CSV file named `Students.csv` with the following columns:

- `Name` : Student's name
- `Math` : Marks in Math
- `Science` : Marks in Science
- `English` : Marks in English
- `History` : Marks in History
- `Computer` : Marks in Computer

**Example:**

| Name   | Math | Science | English | History | Computer |
|--------|------|---------|---------|---------|----------|
| Alice  | 85   | 90      | 78      | 88      | 95       |
| Bob    | 70   | 75      | 80      | 65      | 85       |

## Features & Analysis
1. **Total and Average Marks:** Calculates total and average marks for each student.
2. **Statistical Summary:** Computes minimum, maximum, mean, and standard deviation of total marks.
3. **Top 3 Students:** Identifies the three students with the highest average scores.
4. **Subject-wise Analysis:** Determines which subject has the highest average across all students.
5. **Visualizations:**
   - Bar chart of **total marks** for each student.
   - Line plot of **scores of top 3 students** across all subjects.
   - Pie chart of **average marks per subject**.
   - Histogram of **Math scores distribution**.

## How to Run
1. Make sure Python 3.x is installed.
2. Install required libraries if not already installed:
   ```bash
   pip install pandas numpy matplotlib
