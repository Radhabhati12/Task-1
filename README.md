# Task-1
In this project, we performed several steps to clean and prepare the dataset for analysis:

✅ Handled missing values using .isnull() in Python to identify and fix empty or null entries.

✅ Removed duplicate rows with .drop_duplicates() to avoid repeated data.

✅ Standardized text columns (like gender and country) by converting to lowercase, removing extra spaces, and fixing inconsistent values.

✅ Converted date formats into a consistent style (dd-mm-yyyy) using pd.to_datetime() and .dt.strftime().

✅ Renamed column headers to be clean and uniform — using lowercase letters and replacing spaces with underscores.

✅ Checked and fixed data types so that columns like dates are in datetime format and numeric fields like age or year are properly typed as integers.

These steps ensured the dataset is clean, consistent, and ready for further analysis or visualization.
