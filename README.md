# Task 18: Select Dataset Columns

## Overview
This project demonstrates how to access specific parts of a Pandas DataFrame using the `loc` and `iloc` indexers. The dataset used for this task is the famous **Iris Dataset**.

## Objectives
*   Learn to use `loc` for label-based data selection.
*   Learn to use `iloc` for integer position-based data selection.
*   Successfully extract specific rows and columns from a given DataFrame.

## Tools Used
*   Python
*   Pandas
*   Jupyter Notebook

## Code Explanation
The Python script performs the following operations:
1.  **Loads the Dataset:** Reads `iris_dataset.csv` into a Pandas DataFrame.
2.  **`loc` Selection:** Selects the first 5 rows (index labels 0 to 4) for specific columns by their exact names (`sepal length (cm)` and `species`).
3.  **`iloc` Selection:** Selects rows 10 to 14 and the 1st and 5th columns using their integer positions (0 and 4).

---

## Interview Questions & Answers

**1. What is the difference between loc and iloc?**
*   `loc` is a label-based data selecting method. This means you must pass the name (label) of the row or column you want to select.
*   `iloc` is purely integer-location based indexing for selection by position. You must pass integer indices (0-based) for the rows and columns you want to select.

**2. How do you select a single column in Pandas?**
You can select a single column by using bracket notation with the column name as a string (e.g., `df['column_name']`). Alternatively, if the column name does not contain spaces or special characters, you can use dot notation (e.g., `df.column_name`).

**3. How do you select multiple columns?**
You can select multiple columns by passing a list of column names inside the bracket notation. For example: `df[['column_name_1', 'column_name_2']]`.
