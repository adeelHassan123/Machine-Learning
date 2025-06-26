# Day 15: Working with CSV Data in Python

This folder explores various ways to read, process, and handle CSV (Comma-Separated Values) and TSV (Tab-Separated Values) files using Python, especially with the pandas library.

## Key Concepts Covered

- Reading Local CSV Files:
  - Using pd.read_csv() to load data from a file on your computer.
- Reading CSV from a URL:
  - Downloading and reading CSV data directly from the internet using requests and StringIO.
- Handling Different Separators:
  - Reading TSV files by specifying the sep parameter.
- Customizing Data Loading:
  - Using parameters like header, usecols, skiprows, nrows, and encoding to control how data is read.
- Handling Bad Data:
  - Skipping problematic lines with error_bad_lines.
- Changing Data Types:
  - Using the dtype parameter to set column data types.
- Using Converters:
  - Applying custom functions to columns while reading data.
- Handling Missing Values:
  - Using na_values to specify additional missing value markers.
- Reading Large Files in Chunks:
  - Loading big datasets in smaller parts using the chunksize parameter.

## Libraries Used

- pandas: For all data reading and manipulation tasks.
- requests: For downloading data from the web.

## Why This is Important

Understanding how to efficiently read and process CSV/TSV files is essential for any data analysis or machine learning project. These techniques help you work with real-world data in many formats and sizes.

This folder is a practical guide to mastering data import in Python! 