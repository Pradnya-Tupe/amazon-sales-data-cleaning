# Amazon Sales Data Cleaning and Preprocessing

## Overview
This project contains all files for Task 1: Data Cleaning and Preprocessing of an Amazon sales dataset using Python (Pandas).

## Included Files
- `AmazonSalesData.csv`: Raw data file.
- `data_cleaning.ipynb`: Data cleaning code.
- `AmazonSalesData_cleaned.csv`: Output cleaned data.
- `screenshots/`: Screenshots of cleaning steps or results.

## What Was Done
- Handled missing values using `.isnull()` and dropped or filled them as appropriate.
- Removed duplicate rows with `.drop_duplicates()`.
- Standardized text values (`Region`, `Country`) to lowercase, stripped spaces.
- Converted date columns to a consistent `dd-mm-yyyy` datetime format.
- Cleaned column headers (lowercase, underscores, no spaces).
- Checked and fixed numeric fields and date types.

## How to Reproduce
1. Clone this repository.
2. Run `data_cleaning.ipynb` using Jupyter or run the provided Python script.
3. Output is saved as `AmazonSalesData_cleaned.csv`.

## Sample Output
![Cleaned data demonstration](screenshots/cleaning_demo.png)
