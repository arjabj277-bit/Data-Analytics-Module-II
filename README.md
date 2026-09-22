# Data Analytics using Python – Module II

## BCA503 [T+P] – Hands-on Lab Evaluation 2

**Course:** Data Analytics using Python  
**Module:** II – NumPy & Pandas  
**Program:** BCA, 3rd Year, 5th Semester  
**Department:** SOET, ITM University, Gwalior  
**Academic Session:** 2025–2026

---

## Student Information

**Name:** Arjab Jain  
**Course:** Bachelor of Computer Applications (BCA)  
**Semester:** 5th Semester

---

## Objective

The objective of this practical is to understand and implement NumPy array operations and Pandas data manipulation using the Adult Income Dataset.

The practical covers NumPy array creation, indexing, slicing, advanced indexing, broadcasting, Pandas filtering, grouping, file input/output, and identification of class imbalance.

---

## Dataset

The practical uses the **Adult Income Dataset**.

Dataset source:

- UCI Machine Learning Repository
- Kaggle – Adult Census Income Dataset

The dataset contains demographic and employment-related information such as age, education, occupation, working hours, and income category.

---

## Tasks Performed

### Task 1 – NumPy Indexing, Slicing and Advanced Indexing

- Converted numeric columns into NumPy arrays.
- Performed individual element/field access.
- Performed basic slicing.
- Performed Boolean indexing.
- Performed fancy indexing.
- Compared the outputs of basic and advanced indexing.

### Task 2 – NumPy Broadcasting

- Created a derived array using two numeric columns.
- Used NumPy vectorized operations without an explicit loop.
- Compared NumPy execution time with a Python loop using `%timeit`.
- Verified that both methods produced equivalent results.

### Task 3 – Pandas Multi-Condition Filtering

A subset of records was extracted using three simultaneous conditions based on:

- Age
- Education
- Hours per week

The filtered dataset was saved as a CSV file.

### Task 4 – Pandas GroupBy and File I/O

- Performed a `groupby()` operation.
- Applied a built-in aggregation function.
- Exported the result to CSV.
- Exported the result to XLSX.
- Reloaded both files.
- Compared their data types, shapes, and values.

### Task 5 – Value Counts and Class Imbalance

- Used Pandas `value_counts()`.
- Calculated percentage distribution.
- Identified the dominant income class.
- Calculated the imbalance ratio.
- Discussed the possible risk of class imbalance in later machine-learning analysis.

---

## Project Structure

```text
Data-Analytics-Module-II/
│
├── Dataset/
│   └── adult.csv
│
├── Jupyter_Notebook/
│   └── Module_II_Adult_Income.ipynb
│
├── Python_Code/
│   └── Module_II_Adult_Income.py
│
├── Output_Files/
│   ├── filtered_dataset.csv
│   ├── groupby_result.csv
│   └── groupby_result.xlsx
│
└── Screenshots/
    ├── NumPy indexing
    ├── Broadcasting
    ├── Timing comparison
    ├── Multi-condition filtering
    ├── Round-trip verification
    └── Value counts

Technologies Used
Python
NumPy
Pandas
Jupyter Notebook
Microsoft Excel
GitHub
Learning Outcomes

After completing this practical, the following concepts were implemented:

NumPy arrays
Indexing and slicing
Boolean and fancy indexing
NumPy broadcasting
Vectorized operations
Pandas DataFrame filtering
GroupBy and aggregation
CSV and Excel file handling
Data type and value verification
Class imbalance analysis
Conclusion

This practical provided hands-on experience with NumPy and Pandas using a real-world Adult Income Dataset. NumPy was used for array creation, indexing, slicing, advanced indexing, and broadcasting. Pandas was used to filter records using multiple conditions, perform groupby aggregation, and handle CSV and Excel files. The round-trip verification demonstrated that exported data could be reloaded and checked for consistency. The value_counts() analysis also showed how a dominant class can create imbalance and potentially affect later machine-learning analysis. Overall, the practical strengthened the understanding of data manipulation and preprocessing techniques required for data analytics using Python.
