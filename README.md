# YuvaIntern-Week2-Data-Cleaning
Data cleaning and preprocessing of the UCI Online Retail dataset using Python, Pandas, NumPy, and Scikit-learn.

# Week 2: Data Cleaning and Pre-Processing

## Internship
YuvaIntern – Data Analytics Internship

## Project Overview
This project focuses on cleaning and preprocessing the UCI Online Retail dataset using Python. The objective is to improve data quality and prepare the dataset for further analysis.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Tasks Performed
1. Inspected dataset dimensions, data types, and summary statistics.
2. Identified missing values and duplicate records.
3. Removed exact duplicate rows from a working copy.
4. Investigated missing product descriptions and customer IDs.
5. Examined unusual Quantity and UnitPrice values using the IQR method.
6. Created features such as Revenue, Is_Return, Is_Cancellation, InvoiceMonth, and InvoiceWeekday.
7. Demonstrated StandardScaler, MinMaxScaler, and one-hot encoding.
8. Exported the cleaned dataset, quality summary, and visual output.

## Important Data Quality Decisions
- Missing CustomerID values were not filled with invented identifiers.
- Negative quantities were retained because they may represent product returns.
- Unusual prices and quantities were investigated rather than automatically removed.

## Project Files
- `Week2_Data_Cleaning.ipynb` — analysis and preprocessing code
- `Ouput/Online_Retail_Cleaned.csv` — cleaned dataset
- `Ouput/Final_Data_Cleaning_Summary.csv` — data quality summary
- `Ouput/Missing_Values_Comparison.png` — missing-value comparison chart
- `Ouput/YuvaIntern_Week2_Data_Cleaning_Report.docx` — project report

## Conclusion
This project demonstrates a repeatable data preprocessing workflow and documents important data quality decisions before further analysis.

**Note:** File names listed above should match the actual files in the submitted repository.
