# elevate_labs_internship_task_1
# Task 1 — Data Cleaning & Preprocessing

Dataset Used: Netflix Movies and TV Shows  
Tools: Google Colab, Python (Pandas)

## Steps Performed
1. Loaded the raw dataset and inspected structure using `.info()` and `.head()`.
2. Removed rows with missing `title`.
3. Filled missing values in `country` and `date_added` with `"Unknown"`.
4. Removed duplicate rows using `.drop_duplicates()`.
5. Standardized all column names to lowercase with underscores.
6. Converted `date_added` to datetime format.
7. Ensured `release_year` is integer type.
8. Exported cleaned dataset as `cleaned_netflix_data.csv`.

# Result
The dataset is now cleaned, consistent, and ready for analysis or visualization.

Files Included:
- task1_data_cleaning.ipynb
- cleaned_netflix_data.csv
- README.md
- netflix_titles.csv (original dataset)
