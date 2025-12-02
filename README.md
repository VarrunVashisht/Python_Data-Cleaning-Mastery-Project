# 🧹 Data Cleaning Mastery Project

A complete end-to-end data-cleaning workflow built in Python (pandas) to transform a messy, real-world style dataset into clean, analysis-ready data.

## 📌 Project Overview

This project demonstrates how to clean and prepare complex raw datasets, including fixing typos, handling inconsistent formats, parsing corrupted values, removing duplicates, repairing dates, normalizing categories, detecting outliers, and more. It includes a fully automated pipeline that applies best practices for data quality, validation, and reproducibility.

## 🗂 Dataset

The project uses a purposely messy dataset (`data_cleaning_challenge.csv`) containing 1,000+ rows with realistic data issues across fields such as:

* Names with typos, odd capitalization, extra spaces
* Emails in multiple valid and invalid formats
* Phone numbers in many international styles (and malformed)
* Dates in multiple formats, with corrupted or ambiguous forms
* Age values mixed with text (`"35 yrs"`, `"unknown"`, `"nan"`)
* Income recorded in multiple currency formats, symbols, short forms (`$45k`, `€55,930`, `45000 USD`)
* Geolocation values swapped or out of valid range
* Free-text comments including HTML tags, emojis, injections
* Multi-value columns like `product_codes` with comma/pipe separators
* Boolean fields encoded inconsistently (`Y/N`, `1/0`, `yes/no`, `TRUE/FALSE`)
* Outliers and negative values in monetary fields
* Embedded header fragments and exact duplicated rows

This provides hands-on exposure to nearly all real-world data-cleaning challenges.

---

## ✨ What This Project Teaches

You will learn and practice every major data-cleaning technique:

### ✔ Standardizing & detecting missing values

Convert multiple “null-like” values (`"", NA, N/A, null, —`) into consistent missing markers.

### ✔ Deduplication & anomaly removal

Identify and remove exact duplicates, near-duplicates, and misplaced header rows.

### ✔ Text normalization

Clean names, emails, comments, and other free-text fields.

### ✔ Email & phone validation

Detect malformed emails and normalize phone numbers into a consistent format.

### ✔ Complex date parsing

Handle mixed formats, corrupted strings, ambiguous representations, and missing timestamps.

### ✔ Numeric conversions

Convert messy currencies, numeric strings with symbols, negatives wrapped in parentheses, and short forms (`45k`) into clean float values.

### ✔ Categorical normalization

Fix inconsistencies with countries, contact preferences, subscription statuses, etc.

### ✔ Parsing multi-value fields

Split and clean lists of product codes using smarter splitting logic.

### ✔ Handling outliers

Detect unusually large or negative values using the IQR method and flag them for review.

### ✔ Geospatial cleaning

Fix invalid lat/long pairs, detect swapped coordinates, and correct unrealistic values.

### ✔ Feature engineering

Compute useful fields like days since signup, is_active status, and more.

### ✔ JSON parsing support

Safely extract data from JSON-structured fields embedded as text.

### ✔ Auditability & reproducibility

Keep raw and cleaned columns so every transformation is transparent.

---

## 📁 Project Structure

**Main files included:**

* `data_cleaning_challenge.csv` — messy raw dataset
* `data_cleaning_challenge_cleaned.csv` — cleaned, analysis-ready output
* `data_cleaning_pipeline.py` — full automated cleaning pipeline
* `README.md` — documentation of workflow (this file)

---

## 🚀 How It Works

The cleaning pipeline follows a structured flow:

1. **Load and inspect raw data**
2. **Normalize missing values**
3. **Remove embedded headers and duplicates**
4. **Parse and standardize dates**
5. **Clean and convert numeric/currency fields**
6. **Normalize text-based categories**
7. **Validate & clean emails and phone numbers**
8. **Sanitize free-text fields**
9. **Parse list-type columns**
10. **Detect outliers**
11. **Fix geospatial anomalies**
12. **Produce cleaned output**
13. **Print diagnostics and summary statistics**

---

## 🎯 Learning Outcomes

By completing this project, you will be able to:

* Clean any dirty dataset using Python
* Build robust, reusable cleaning pipelines
* Detect and fix real-world data inconsistencies
* Create analysis-ready, reliable datasets
* Understand the principles behind professional data preprocessing

This project sets you up for success in:

* Data analysis
* Machine learning preprocessing
* ETL / data engineering
* Analytics engineering (dbt, Airflow, etc.)
* Real-world business data cleaning scenarios

---

## 📝Author:
## Varrun Vashisht

Just tell me!
