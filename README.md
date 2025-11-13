# Data-cleaning_Task1
Data Cleaning of the Dataset- Customer Personality Analysis

**Project:** Data Cleaning and Preprocessing - Customer Personality Analysis
**Author:** Koteswara Rao Patchava 
**Date:** 2025-11-13

## Files
- `marketing_campaign.xlsx` — small sample of original raw data
- `marketing_campaign_cleaned.xlsx` — cleaned dataset after processing
- `image.png` — Excel screenshots (Text to Columns, blanks, format cells)

## Summary of changes
- Removed duplicate rows.
- Identified and handled missing values 
- Standardized text values (education, marital_status, gender).
- Converted date columns to `dd-mm-yyyy` format.
- Renamed columns to lowercase with underscores.
- Corrected data types (ID as text, age as integer, income as decimal, date as date).

## How I did it (Excel)
1. Opened raw data in Excel.
2. Used **Data → Text to Columns** Delimited to split merged column into fields.
3. Applied **Data → Filter** and checked each column for **(Blanks)**.
4. Filled blanks where appropriate (Home → Go To Special → Blanks → enter value / formula).
5. Removed duplicates: **Data → Remove Duplicates**.
6. Standardized text with **Find & Replace**, `LOWER()` and Flash Fill.
7. Converted dates: selected column → **Format Cells → Date (dd-mm-yyyy)**, or used `=DATEVALUE()` if needed.
8. Set column formats: ID → Text, numeric columns → Number, categorical → Text.
9. Saved cleaned dataset as `marketing_campaign_cleaned.xlsx`. Screenshots in `image.png`.
