# Day 12: Exploring Python Libraries for Data Analysis

This notebook demonstrates how to use essential Python libraries for data analysis, focusing on reading and exploring a real-world HR dataset.

## Libraries Used

1. pandas
   - Purpose: Powerful library for data manipulation and analysis.
   - Key Features:
     - Reading and writing data from various file formats (CSV, Excel, SQL, etc.)
     - Data cleaning, filtering, and transformation
     - Handling missing data
     - Grouping, aggregation, and summarization
   - Usage in this notebook:
     - Imported as pd
     - Used to read a CSV file (HR_comma_sep.csv) into a DataFrame for analysis

2. numpy
   - Purpose: Fundamental package for scientific computing with Python.
   - Key Features:
     - Efficient array operations
     - Mathematical, logical, and statistical functions
     - Used as the backbone for many data science libraries (including pandas)
   - Usage in this notebook:
     - Imported to support numerical operations (though not directly used in the shown code, it is a common dependency for pandas)

## Dataset: HR_comma_sep.csv
- Description:
  - Contains HR data for employees, including satisfaction level, evaluation scores, project counts, work hours, and more.
  - Columns include:
    - satisfaction_level: Employee satisfaction (0-1)
    - last_evaluation: Last evaluation score (0-1)
    - number_project: Number of projects handled
    - average_montly_hours: Average monthly working hours
    - time_spend_company: Years spent at the company
    - Work_accident: Whether the employee had a work accident (0/1)
    - left: Whether the employee left the company (0/1)
    - promotion_last_5years: Promotion in the last 5 years (0/1)
    - sales: Department
    - salary: Salary level (low/medium/high)

## Step-by-Step Concepts

1. Installing Libraries
   - Used pip install pandas and pip install numpy to ensure the required libraries are available.
   - Tip: In Jupyter, prefix with ! (e.g., !pip install pandas).

2. Importing Libraries
   import pandas as pd
   import numpy

3. Reading Data
   df = pd.read_csv("HR_comma_sep.csv")
   - Reads the CSV file into a DataFrame called df.
   - DataFrames are like tables (rows and columns) and are the core data structure in pandas.

4. Displaying Data
   print(df)
   - Prints the entire DataFrame to view the data.
   - Useful for a quick look at the dataset structure and contents.

## Additional Tips
- Data Exploration:
  - Use df.head() to see the first few rows.
  - Use df.info() to get a summary of the DataFrame (column types, non-null counts).
  - Use df.describe() for basic statistics (mean, std, min, max, etc.).
- Why pandas and numpy?
  - They are industry-standard tools for data analysis and manipulation in Python.
  - Learning these libraries is foundational for any data science or machine learning workflow.

This notebook is a starting point for anyone new to data analysis in Python. Mastering pandas and numpy will make working with data much easier and more efficient!
