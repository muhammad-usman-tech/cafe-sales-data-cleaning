# Cafe Sales Data Cleaning and ETL

## Project Overview

This project focuses on cleaning and preparing a dirty cafe sales dataset using Python and Pandas.

The main objective is to practice the ETL process (Extract, Transform, Load) by inspecting the dataset, identifying data-quality issues, handling missing values, converting data types, removing duplicates, and validating the cleaned data.

This is an independent learning project developed to strengthen practical data-cleaning and data-preparation skills.

## Dataset Overview

- **Dataset:** Dirty Cafe Sales
- **Original Records:** 10,000
- **Original Attributes:** 8
- **Data Type:** Structured sales transaction data
- **Time Period:** January 2023 – December 2023 (based on observed date boundaries)

The dataset contains cafe transaction information, including quantities, prices, total spending, payment methods, locations, and transaction dates.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Google Colab

## ETL Workflow

The project follows these main stages:

1. **Data Inspection** – Examined the dataset's dimensions, columns, sample records, and data types.
2. **Text Cleaning** – Removed unnecessary leading and trailing spaces from text columns.
3. **Standardization** – Standardized column names using lowercase letters and underscores.
4. **Error Handling** – Identified and converted invalid entries such as `ERROR`, `UNKNOWN`, and empty strings into missing values.
5. **Data Type Conversion** – Converted numerical columns and transaction dates into appropriate data types.
6. **Duplicate Handling** – Identified and removed exact duplicate records.
7. **Missing-Value Analysis** – Calculated missing-value counts and percentages.
8. **Missing-Value Treatment** – Applied different handling strategies to categorical and numerical columns.
9. **Data Validation** – Checked date boundaries, data types, missing values, and duplicate records.
10. **Data Export** – Exported the cleaned dataset as a CSV file.

## Data Cleaning Techniques

The following techniques were practiced:

- `str.strip()` for removing unnecessary whitespace.
- `str.replace()` for standardizing column names.
- `replace()` for identifying invalid entries.
- `pd.to_numeric()` for numerical conversion.
- `pd.to_datetime()` for date conversion.
- `drop_duplicates()` for duplicate removal.
- `dropna()` for handling missing transaction IDs.
- Median imputation for numerical missing values.
- Filling categorical missing values with `UNKNOWN`.
- Missing-value percentage analysis.

## Data Quality Checks

The project included checks for:

- Missing values
- Exact duplicate records
- Duplicate transaction IDs
- Invalid numerical entries
- Date conversion errors
- Minimum and maximum transaction dates
- Data types after transformation

## Learning Outcomes

Through this project, I practiced:

- Understanding data quality issues in a real-world-style dataset.
- Performing ETL operations using Pandas.
- Handling missing and inconsistent values.
- Converting columns into appropriate data types.
- Applying different missing-value treatment techniques.
- Validating cleaned data.
- Exporting prepared datasets for further analysis.

## Challenges and Areas for Improvement

During this project, I learned that cleaning data requires more than simply removing missing values and duplicates.

Some important considerations include:

- Understanding the meaning of missing values before filling them.
- Checking whether transaction IDs must be unique.
- Investigating negative or unusual quantities.
- Validating relationships between quantity, price, and total spending.
- Handling missing transaction dates carefully when performing time-based analysis.

## Conclusion

This project provided practical experience in preparing an imperfect dataset for further analysis.

It strengthened my understanding of the ETL process and helped me practice making data-cleaning decisions using Python and Pandas.

This is an independent learning project, and the cleaning process can be further improved through additional validation and analysis.
