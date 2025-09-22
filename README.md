# Data Cleaning for Customer Dataset

This project contains a Jupyter Notebook performing essential data cleaning tasks on a customer dataset CSV file.

## What was done

1. **Loaded Data**  
   The dataset was imported using pandas, with special handling for tab-delimited data to correctly parse all columns.

2. **Handled Missing Values**  
   Missing values were identified using `.isnull()` and optionally handled by removing or imputing them as needed.

3. **Removed Duplicates**  
   Duplicate rows were removed using `.drop_duplicates()` to keep the dataset unique.

4. **Standardized Text Columns**  
   Text categorical columns such as `Education` and `Marital_Status` were standardized by converting to lowercase and trimming whitespace.

5. **Converted Date Formats**  
   The `Dt_Customer` date column was cleaned and converted to a uniform `dd-mm-yyyy` format.

6. **Renamed Columns**  
   Column headers were made uniform by converting all to lowercase and replacing spaces with underscores.

7. **Fixed Data Types**  
   Numeric columns (e.g., `Year_Birth`, `Income`, `Kidhome`) were converted to appropriate numeric types, and date columns to datetime format for accurate processing.

## Usage

Open the Jupyter Notebook, update the file path to your CSV dataset, and run the cells sequentially to clean and prepare your data for analysis.

---

This workflow ensures a clean, consistent, and analysis-ready dataset from raw CSV data.

