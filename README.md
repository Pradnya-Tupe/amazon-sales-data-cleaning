# Amazon Sales Data Cleaning

This project showcases a data cleaning task on a raw sales dataset from Amazon, using Python and Pandas. The goal is to prepare the data for analysis by removing inconsistencies, handling missing values, and ensuring uniform formatting.

---

## 📌 Objective

- Load and inspect the raw dataset
- Handle missing values
- Remove duplicate entries
- Standardize text formats (e.g., country names)
- Convert date columns to proper datetime format
- Clean and normalize column names
- Ensure correct data types for numeric fields
- Export a cleaned version of the dataset

---

## 🧰 Tools Used

- Python 3.x
- Pandas
- Jupyter Notebook (optional)

---

## 🧼 Cleaning Steps

1. **Loaded** the dataset using `pd.read_csv()`
2. **Dropped** rows with missing values in key columns: `Order Date` and `Country`
3. **Filled** missing values in `'Item Type'` with `'Unknown'`
4. **Removed** duplicate rows using `drop_duplicates()`
5. **Standardized** values in `Country` and `Region` (lowercase, trimmed)
6. **Converted** `'Order Date'` and `'Ship Date'` columns to `datetime` format
7. **Cleaned column names**: converted to snake_case and lowercase
8. **Converted** numerical columns like `units_sold`, `unit_price`, etc., to appropriate numeric types
9. **Exported** the cleaned dataset as `AmazonSalesData_cleaned.csv`

---

## 📁 File Structure




1. Clone the repo:
```bash
git clone https://github.com/your-username/amazon-sales-data-cleaning.git
