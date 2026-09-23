# DecodeLabs Data Cleaning & Preparation

## Project Overview

This project was completed as part of the DecodeLabs Data Analytics Industrial Training Program.

The objective of this project was to clean and prepare a raw dataset by identifying and handling missing values, duplicate records, incorrect data formats, and invalid numeric values.

## Objective

The main objectives of this project were:

- Identify and handle missing values
- Check for duplicate Order IDs
- Check for duplicate rows
- Validate date formatting
- Check numeric columns for invalid values
- Prepare a clean and reliable dataset

## Tools Used

- Microsoft Excel
- Data Cleaning
- Data Validation
- Excel Functions and Formatting

## Data Cleaning Performed

### 1. Missing Values

Blank values in the `CouponCode` column were identified and replaced with:

`NO COUPON`

### 2. Duplicate Check

Duplicate `OrderID` values were checked.

The complete dataset was also checked for duplicate rows.

### 3. Date Validation

Date values were checked to ensure consistent formatting.

### 4. Numeric Validation

The following numeric columns were checked for invalid or non-positive values:

- Quantity
- UnitPrice
- ItemInCart
- TotalPrice

## Change Log

A separate Change Log sheet has been included in the Excel workbook to document:

- Issue Found
- Action Taken
- Result

## Final Result

The cleaned dataset was prepared after performing data quality checks for missing values, duplicates, date formatting, and invalid numeric values.

## Project Files

- `DecodeLabs_Data_Cleaning_Project.xlsx` – Complete workbook containing Raw Data, Cleaned Data and Change Log.

## Key Learning

This project helped me understand the importance of data cleaning and data quality before performing further analysis.
