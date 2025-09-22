# Netflix Data Cleaning & Preprocessing

## Objective
Clean and prepare the Netflix Movies and TV Shows dataset by handling missing values, duplicates, inconsistent text formats, date conversions, and numeric conversions.

## Dataset
- Columns: show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description, duration_minutes
- Source: Kaggle – Netflix Movies and TV Shows dataset

## Steps Performed
1. Checked and replaced missing values:
   - Text columns: 'Unknown'
   - Numeric columns: 0
   - Date column: 2000-01-01
2. Removed duplicate records
3. Standardized text fields (lowercase/type, title case/country)
4. Converted column headers to snake_case
5. Extracted numeric duration from 'duration' column
6. Fixed data types (release_year & duration_minutes as integers, date_added as datetime)

## Output
- Cleaned dataset saved as `Netflix_Cleaned.csv`
