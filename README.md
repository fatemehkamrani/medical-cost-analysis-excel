# Medical Cost Analysis in Excel

This project started as an Excel exercise from the Data Analyst training program at Tose'e Institute, taught by Dr. Majid Eyvazian.

The assignment asked for a formula-based analysis of a medical cost dataset. After completing the required questions, I added a few alternative formula methods, PivotTables, validation checks, and documentation to compare different approaches and verify the results.

---

## Assignment Information

- Institute: Tose'e Institute
- Instructor: Dr. Majid Eyvazian
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

I kept the original data columns unchanged and added helper columns for the regional and BMI classifications required in the exercise.

I completed the main analysis with Excel formulas and structured references. Then I solved selected calculations again using other formula techniques and compared the results.

Finally, I used PivotTables as another way to check the main outputs and added PASS / CHECK formulas for validation.

---

## Additional Work

Beyond the required calculations, I added a few extra parts to the workbook:

- Converted the dataset into an Excel Table
- Added helper columns for region and BMI classifications
- Added simple data quality checks
- Used structured references instead of fixed cell ranges
- Solved selected calculations directly from the source columns without helper columns
- Repeated the analysis using SUMPRODUCT
- Used FILTER and LET + FILTER as additional approaches
- Built PivotTables to check the formula results
- Compared outputs across different methods
- Added PASS / CHECK validation formulas
- Added a Documentation sheet for the project rules, assumptions, and workbook structure

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

## Excel Features and Functions Used

- Excel Tables
- Structured References
- SWITCH
- IFS
- COUNTIF / COUNTIFS
- SUMIF
- AVERAGEIF / AVERAGEIFS
- SUMPRODUCT
- FILTER
- LET
- PivotTables
- Conditional Formatting
- Validation checks

---

## Key Results

- North: 649 records
- South: 689 records
- East: 688 records
- West: 650 records
- BMI < 20: 41 records
- BMI 20–30: 592 records
- BMI > 30: 705 records
- Average cost for non-smokers: 8,434.27
- Average cost for smokers with BMI > 30: 41,692.81

---

## Data Quality Notes

- No missing values were found
- One exact duplicate record was found and kept because there was no unique ID to confirm that it was an accidental duplicate
- The original source columns were kept unchanged
- Helper columns were added separately for the analysis

---

## Validation

I cross-checked the main results using:

- The primary formula-based analysis
- Alternative formula methods
- PivotTables
- PASS / CHECK comparison formulas

The selected validation metrics returned consistent results across the different methods.

---

## Project Files

- [Excel Workbook](./Fatemeh_Kamrani_Medical_Cost_Analysis.xlsx)
- [Original Assignment](./docs/Excel_Exercise_01_Assignment.pdf)

```text
medical-cost-analysis-excel/
│
├── README.md
├── Fatemeh_Kamrani_Medical_Cost_Analysis.xlsx
└── docs/
    └── Excel_Exercise_01_Assignment.pdf
