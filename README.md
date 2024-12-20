## Pandas Challenge
---
# PyCitySchools Analysis

## Table of Contents
- [Description](#description)
- [Data Files](#data-files)
- [Features](#features)
- [Installation](#installation)
- [Results](#results)
- [Observable Trends](#observable-trends)

---

## Description

**PyCitySchools** is a Python-based project that analyzes school performance data. The analysis includes comparisons of test scores, passing rates, and budgets for **charter schools** and **district schools**. Results highlight significant trends, including the relationships between per-student budgets and overall performance.

This project uses **Jupyter Notebook** for exploratory data analysis (EDA) and visualization.

---

## Data Files

| File Name              | Description                                   |
|------------------------|-----------------------------------------------|
| `schools_complete.csv` | Dataset containing information on schools.   |
| `students_complete.csv`| Dataset containing student performance data. |
| `PyCitySchools.ipynb`  | Jupyter Notebook performing the analysis.    |
| `analysis.txt`         | Summary of key trends observed in the data.  |

---

## Features

- **School Performance Analysis**:
  - Calculates average math and reading scores for schools.
  - Determines overall passing rates for students.

- **Charter vs. District Schools**:
  - Compares subject performance between charter and district schools.
  - Analyzes the relationship between budget per student and school performance.

- **Data Aggregation**:
  - Merges datasets for schools and students.
  - Summarizes performance metrics for individual schools.

---

## Installation

1. **Prerequisites**:
   - Python 3.x
   - Required libraries (if any) listed in `requirements.txt`.

2. **Setup**:
   - Clone this repository or download the project files.
     
   - Install dependencies (if needed):
     ```bash
     pip install -r requirements.txt
     ```
---

## Results

### Key Observations

The following insights were derived from the analysis:
1.	Overall Passing Rates:
   - Charter Schools: 89% to 91% passing.
   - District Schools: 52% to 54% passing.
2.	Budget Impact:
   - District schools have a higher budget per student but perform worse overall in test scores and passing rates.
3.	Performance Comparison:
   - Charter schools consistently outperform district schools in both math and reading scores.
---

## Observable Trends

1.	Charter Schools Perform Better:
   - Higher average subject scores and passing rates across all grades.
2.	Budget vs. Performance:
   - Higher per-student budgets in district schools do not correlate with better performance.
   - This raises questions about the efficiency of budget allocation in district schools.
---
