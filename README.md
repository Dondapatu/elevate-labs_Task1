# elevate-labs_Task1

# Netflix Dataset Cleaning – Task 1

## Cleaning Summary

- Filled missing values in:
  - `director`, `cast`, `country` → "Unknown"
- Converted `date_added` to `dd-mm-yyyy` format and removed unparseable entries
- Removed duplicate rows
- Standardized text fields:
  - `type` to lowercase
  - `country` to title case
  - `rating` to uppercase
- Renamed column headers to snake_case
- Converted `release_year` to integer type
- Final cleaned dataset saved as `netflix_cleaned.csv`

## Tools Used
- Python 3.x
- Pandas
