# Employee Data Cleaning and Analysis

## Project Overview

This student project explores data cleaning, preparation, and exploratory data analysis using a practice employee dataset. The goal was to identify data quality issues, prepare the dataset for analysis, and summarize patterns in employee salaries, performance ratings, and joining dates.

## Objectives

- Inspect the dataset for data quality issues.
- Standardize inconsistent department labels.
- Investigate malformed email data without making unsupported corrections.
- Analyze average salary and performance by department.
- Examine the relationship between employee age and performance ratings.
- Summarize employee joining trends by year.
- Identify the highest-paid employees in the dataset.

## Tools Used

- Excel
- Python
- pandas
- Jupyter Notebook

## Data Cleaning

The project included inspecting the dataset, checking for duplicate records and missing values, standardizing department labels, and reviewing data types.

A malformed email address was flagged for verification rather than corrected without supporting information.

## Analysis and Key Findings

### 1. Average Salary by Department

| Department | Average Salary |
|---|---:|
| HR | $51,250.00 |
| IT | $69,000.00 |
| Marketing | $62,083.33 |
| Sales | $57,666.67 |

IT had the highest average salary among the departments in this dataset, while HR had the lowest.

### 2. Average Performance Rating by Department

| Department | Average Performance Rating |
|---|---:|
| HR | 3.467 |
| IT | 4.311 |
| Marketing | 3.750 |
| Sales | 3.889 |

IT had the highest average performance rating in the dataset. These descriptive results do not establish that higher salaries cause better performance.

### 3. Age and Performance

The Pearson correlation coefficient between age and performance rating was approximately **0.459**, indicating a moderate positive linear relationship in this dataset. Correlation does not establish causation.

### 4. Employees Joining by Year

| Year | Number of Employees |
|---|---:|
| 2017 | 2 |
| 2018 | 4 |
| 2019 | 8 |
| 2020 | 7 |
| 2021 | 5 |
| 2022 | 3 |

The largest number of employees in the reported results joined in 2019.

### 5. Highest-Paid Employees

| Employee | Department | Salary |
|---|---|---:|
| Joshua King | IT | $74,000 |
| Linda Martinez | IT | $73,000 |
| Paul Martin | IT | $72,000 |

These names and values are reported from the project analysis. The underlying dataset should be checked to confirm that the displayed salaries were not imputed or otherwise altered during cleaning.

## Limitations

- This is a student project using a practice dataset, not a real client engagement.
- The findings describe the dataset and should not be generalized to a real workforce.
- The malformed email requires verification against a reliable source.
- Results should be validated against the final cleaned dataset and analysis notebook before being used for decisions.

## Project Files

- `Employee_Data_Analysis.ipynb` — analysis notebook.
- `employee_data_cleaned.csv` — cleaned dataset, if included.
- `report/` — project report, if included.
- `visuals/` — charts, if included.

## What I Learned

This project provided practical experience with data quality checks, data standardization, exploratory analysis, descriptive statistics, correlation analysis, and communicating findings through tables and written reporting.

## Project Type

Student portfolio project.
