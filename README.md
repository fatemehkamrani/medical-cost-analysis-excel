
# Medical Cost Analysis in Excel
This project was completed as part of an Excel data analysis exercise in the Data Analyst training program at Tose'e Institute, under the guidance of Dr. Ayvazian.
The original assignment focused on solving a set of medical cost analysis questions using Excel formulas. I used the assignment as a base and then expanded the workbook with additional methods, validation checks, PivotTables, and documentation to make the project more complete and easier to review.

---
## Assignment Information
- Institute: Tose'e Institute
- Instructor: Dr. Ayvazian
- Course: Data Analyst Training Program
- Exercise: Excel Exercise 01

The original assignment file is included in the `docs` folder for reference.
---
## Original Assignment

The original exercise required analyzing a medical cost dataset in Excel and answering the following questions:

1. Divide the records into North and South regions and calculate:
   - Record count
   - Total cost
   - Average BMI

2. Divide the records into East and West regions and calculate:
   - Record count
   - Total cost
   - Average BMI

3. Divide the records into three BMI groups:
   - BMI < 20
   - BMI 20–30
   - BMI > 30

   Then calculate:
   - Record count
   - Average cost

4. Calculate the average cost for non-smokers.

5. Calculate the average cost for smokers with BMI above 30.

---
## My Approach
I first kept the original dataset unchanged and added a few helper columns for the classifications needed in the analysis.
The main analysis was completed using Excel formulas and structured references. After that, I repeated the same calculations using different methods to make sure the results were consistent.
I also created PivotTables as an additional validation layer and added simple PASS / CHECK controls to compare the outputs.

---

## Additional Work
The original assignment only required the main calculations, but I added several extra parts to make the workbook more complete:

- Converted the dataset into an Excel Table
- Added helper columns for regional and BMI classifications
- Added simple data quality checks
- Used structured references instead of fixed cell ranges
- Solved the same questions with multiple formula approaches
- Used Direct Criteria without helper columns
- Used SUMPRODUCT
- Used FILTER
- Used LET + FILTER
- Created PivotTables for validation
- Compared results across different methods
- Added PASS / CHECK validation
- Added a Documentation sheet with assumptions, rules, and workbook structure
---

## Workbook Structure
The workbook is organized into five sheets:

### Data
Contains the original dataset and the helper columns used for classification.

### Analysis
Contains the main answers to the five assignment questions.

### Alternative Methods
Shows different ways to calculate the same results using other Excel formulas.

### Pivot Analysis
Uses PivotTables to check the results from the formula-based analysis.

### Documentation
Contains the project overview, business rules, data quality notes, methods used, and workbook structure.

---

## Methods and Excel Features Used
- Excel Tables
- Structured References
- SWITCH
- IFS
- COUNTIF
- COUNTIFS
- SUMIF
- AVERAGEIF
- AVERAGEIFS
- SUMPRODUCT
- FILTER
- LET
- PivotTables
- Conditional Formatting
- Formula Validation

---

## Key Results
Some of the main results from the analysis are:

- North records: 649
- South records: 689
- East records: 688
- West records: 650
- BMI < 20 records: 41
- BMI 20–30 records: 592
- BMI > 30 records: 705
- Average cost for non-smokers: 8,434.27
- Average cost for smokers with BMI above 30: 41,692.81

---

## Data Quality Notes
During the review of the dataset:
- No missing values were found
- One exact duplicate row was identified
- The duplicate was kept because the dataset does not include a unique patient or record ID
- The original source columns were not modified
- Helper columns were added separately for analysis

---

## Validation
The final results were checked in several ways:
- Main formula-based analysis
- Alternative formula methods
- PivotTables
- Cross-checks between outputs

The goal of the validation was to make sure the same calculation produced the same result regardless of the method used.
---

## Files

```text
medical-cost-analysis-excel/
│
├── README.md
├── Fatemeh_Kamrani_Medical_Cost_Analysis.xlsx
└── docs/
    └── Excel_Exercise_01_Assignment.pdf
