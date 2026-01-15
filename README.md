# Data-Analyst-Internship-Task-1 
## Excel Basics: Data Cleaning & Formatting

###  Task Objective
The objective of this task is to clean and standardize a real-world dataset using Microsoft Excel, following professional data analysis practices. The task focuses on handling missing values, duplicates, inconsistent text formatting, and incorrect data types.

---

###  Dataset Used
- **Dataset Name:** Netflix Movies and TV Shows
- **Source:** Kaggle
- **Format:** CSV
- **Size:** ~8,000+ rows

---

###  Tools Used
- Microsoft Excel (Primary)
- GitHub (Submission & Version Control)

---

###  Steps Performed

1. **Dataset Import**
   - Downloaded the dataset in CSV format.
   - Opened it in Excel ensuring proper delimiter separation and headers.

2. **Raw Data Preservation**
   - Saved the original dataset as `Raw_Data.xlsx`.
   - Ensured raw data was never modified.

3. **Data Exploration**
   - Applied filters to all columns.
   - Used Freeze Panes to lock header rows.

4. **Missing Value Identification**
   - Identified missing values using filters.
   - Highlighted blanks using conditional formatting.
   - Retained missing values where appropriate instead of guessing.

5. **Duplicate Handling**
   - Created a backup sheet before removing duplicates.
   - Removed duplicates using key columns such as `show_id` and `title`.

6. **Text Standardization**
   - Standardized text fields using Excel functions:
     - `TRIM()` to remove extra spaces
     - `PROPER()` and `UPPER()` for consistent capitalization
   - Applied to columns like title, director, country, and rating.

7. **Data Type Validation**
   - Validated date columns and numeric fields.
   - Ensured categorical values had no spelling inconsistencies.

8. **Cleaned Data Sheet**
   - Created a separate `Cleaned_Data` sheet.
   - Copied only finalized, cleaned values.

9. **Data Quality Notes**
   - Added a `Data_Quality_Notes` column to document issues such as missing values and inconsistencies.

10. **Final**
