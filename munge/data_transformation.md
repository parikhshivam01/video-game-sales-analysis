# Data Transformation (Module 4)

The following transformations were applied to the dataset:

- **Filtered** out rows with missing values in `Year`, `Genre`, or `Publisher`.
- **Standardized** column names to lowercase.
- **Created** a new column `Total_Sales` by summing `NA_Sales`, `EU_Sales`, `JP_Sales`, and `Other_Sales`.
- **Converted** `Year` to integer type.
