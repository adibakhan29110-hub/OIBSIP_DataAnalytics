# Task 3 – Data Cleaning Report

## Project Overview
This project focuses on cleaning a real-world dataset to ensure data accuracy, consistency, and reliability.  
The dataset used is the **Airbnb New York City (2019)** dataset, which contains information about listings, hosts, pricing, availability, and reviews.

Data cleaning is a critical step in data analysis, as poor data quality can lead to misleading insights and incorrect business decisions.

---

## Dataset Information
- **Dataset Name:** Airbnb NYC 2019
- **Source:** Public dataset (Kaggle)
- **Records:** ~48,000 rows
- **Features:** 16 columns
- **Format:** CSV

---

## Objectives
- Handle missing and inconsistent data
- Remove duplicate records
- Standardize categorical data
- Detect and treat outliers
- Prepare a clean dataset for further analysis

---

## Data Integrity Checks
Initial inspection was performed to understand the dataset structure and data types.  
Column names, null values, and duplicate records were examined to ensure data reliability.

---

## Missing Data Handling
Several columns contained missing values, primarily:
- `reviews_per_month`
- `last_review`
- `name`
- `host_name`

### Actions Taken:
- Missing values in **`reviews_per_month`** were replaced with `0`
- Missing values in **`last_review`** were filled with `"Not Available"`
- Text fields were inspected to ensure usability

These decisions preserve data consistency while minimizing data loss.

---

## Duplicate Removal
Duplicate records were identified using full-row comparison.

### Actions Taken:
- All duplicate rows were removed using Pandas’ `drop_duplicates()` method

This ensures each listing appears only once in the dataset.

---

## Data Standardization
To maintain consistency across categorical columns:

### Columns Standardized:
- `room_type` → converted to lowercase and trimmed
- `neighbourhood_group` → converted to title case

Standardization improves readability and prevents category mismatch during analysis.

---

## Outlier Detection and Treatment
Outliers were identified in numerical columns such as:
- `price`
- `minimum_nights`

### Actions Taken:
- Visual inspection using boxplots
- Extremely high price values were filtered out (price > 500)

This step reduces skewness and improves analysis reliability.

---

## Final Cleaned Dataset
- All missing values addressed
- Duplicates removed
- Categorical variables standardized
- Outliers treated

The cleaned dataset was saved for future analysis:

