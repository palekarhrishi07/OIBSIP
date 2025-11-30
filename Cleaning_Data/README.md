# Cleaning Data – OIBSIP Internship Project

## 📌 Project Objective
The goal of this task is to clean a raw dataset by handling missing values, removing duplicates, standardizing columns, and ensuring data consistency.

## 📁 Dataset Used
- Airbnb NYC Dataset (Dataset 1 from Oasis Infobyte – Data Cleaning Task)

## 🛠️ Steps Performed
1. Loaded the raw dataset into a pandas DataFrame.
2. Identified missing values across all columns.
3. Filled missing values:
   - `name` and `host_name` → "Unknown"
   - `last_review` → "No Review"
   - `reviews_per_month` → 0
4. Removed duplicate rows from the dataset.
5. Standardized column names and cleaned text fields.
6. Ensured correct data types for all columns.
7. Saved the final cleaned dataset as `cleaned_dataset.csv`.

## 📊 Final Output Files
- `cleaning_data.ipynb` – Notebook containing the full cleaning process
- `raw_dataset.csv` – Original dataset
- `cleaned_dataset.csv` – Final cleaned dataset

## ✔️ Project Status
**Completed Successfully**


