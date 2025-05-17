# Layoffs Data Cleaning (SQL)

This SQL script performs data cleaning on the `layoffs` dataset. 

### Main Steps:
- Duplicate removal using `ROW_NUMBER()`
- Whitespace trimming and text standardization
- Industry value correction (e.g., `Crypto%` → `Crypto`)
- Date conversion to standard format (`DATE`)
- Null value handling and deletion
- Column type modifications

Used MySQL functions like:
- `ROW_NUMBER() OVER()`
- `TRIM()`
- `STR_TO_DATE()`
- `JOIN` for data inference

---
