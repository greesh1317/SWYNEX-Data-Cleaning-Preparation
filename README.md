# SWYNEX – Data Cleaning & Preparation

## Project Overview
This project focuses on cleaning and preparing a retail store sales dataset for further analysis as part of Task 1 of the SWYNEX internship.

The dataset was cleaned using Microsoft Excel.

## Dataset Information
- **Dataset:** Retail Store Sales
- **File:** `SWYNEX_Retail_Sales_Cleaned.csv`
- **Records:** 12,575 transactions
- **Columns:** 11

## Data Cleaning Activities

### 1. Missing Values
- Identified missing values across the dataset.
- Recovered 609 missing `Price Per Unit` values using `Total Spent / Quantity`.
- Left 1,213 missing Item values unchanged because they could not be reliably identified.
- Left 604 missing Quantity and Total Spent records unchanged.
- Retained 4,199 blank Discount Applied values because blank does not necessarily mean FALSE.

### 2. Duplicate Records
- Checked Transaction IDs for uniqueness.
- Checked for duplicate records across the original dataset columns.
- No duplicate records were found.

### 3. Data Validation
- Checked consistency between Category and Item codes.
- Verified calculated totals against Total Spent.
- No calculation mismatches were found among records with sufficient information.
- Checked payment methods, locations and transaction dates.

### 4. Data Integrity
- Preserved original records where values could not be reliably recovered.
- Used validation checks to confirm recovered price values.
- Removed temporary helper columns after completing validation.

## Tools Used
- Microsoft Excel
- GitHub

## Project Outcome
The dataset was cleaned, validated and exported as a CSV file. Missing values that could not be reliably recovered were retained rather than replaced with assumptions.

## Repository Contents
- `SWYNEX_Retail_Sales_Cleaned.csv` – Cleaned dataset.
- `README.md` – Project documentation.

---

**Internship Task:** Task 1 – Data Cleaning & Preparation  
**Organization:** SWYNEX Technologies
