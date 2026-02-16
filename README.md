# Employee Data Cleaning & Data Quality Validation (Excel)

## Project Overview
This project demonstrates a structured, end-to-end data cleaning and data quality validation workflow using Microsoft Excel.

The objective of the project is to transform a messy employee dataset into a clean, reliable, and analysis-ready dataset by applying validation rules, standardization logic, and record-level quality checks — without removing data that may still be valuable for business review.

---

## Dataset Structure
The Excel workbook is organized into the following sheets:

- **01_Raw_Employee_Data**  
  Contains the original uncleaned employee dataset with inconsistencies, missing values, and invalid entries.

- **02_Cleaned_Employee_Data**  
  Cleaned dataset with additional validation columns, standardized fields, and record-level status flags.

- **03_Data_Quality_Metrics**  
  Summary metrics showing invalid percentages for critical fields and overall data readiness.

---

## Data Cleaning & Validation Rules
The following validation checks were applied:

- **Age Validation** – Ensures age values fall within acceptable ranges
- **Salary Validation** – Identifies invalid or inconsistent salary entries
- **Join Date Validation** – Verifies valid date formats and logical timelines
- **Phone Number Validation** – Flags invalid phone number formats
- **Performance Score Standardization** – Normalizes performance categories into numeric ratings
- **Record Status Logic** – Records are marked as *Approved* or *Needs Review* based on validation outcomes

Invalid records were **flagged instead of deleted** to preserve business context and data integrity.

---

## Key Highlights
- Business-friendly data cleaning approach
- No hard deletion of records
- Clear validation indicators for each critical field
- Data quality metrics to support decision-making
- Fully implemented using Excel formulas and logic

---

## Tools Used
- Microsoft Excel  
- Data validation rules  
- Conditional logic and formulas  
- Summary metrics and quality checks  

---

## Outcome
The final dataset is clean, traceable, and ready for downstream analysis while maintaining transparency around data quality issues and review requirements.

This project reflects real-world data preparation practices commonly used before reporting or advanced analytics.
