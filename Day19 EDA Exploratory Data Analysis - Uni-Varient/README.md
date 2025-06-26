# Day 19: Exploratory Data Analysis (EDA) - Univariate

This folder focuses on univariate EDA, which means analyzing one variable at a time to understand its distribution, summary statistics, and potential issues.

## Key Concepts Covered

- Loading Data:
  - Using pandas to read the dataset (train.csv).
- Data Overview:
  - Viewing the structure and types of data using df.info().
- Checking for Missing Values:
  - Using df.isnull().sum() to find missing data.
- Descriptive Statistics:
  - Using df.describe() to get statistics like mean, median, min, max, etc.
- Finding Duplicates:
  - Using df.duplicated().sum() to check for duplicate rows.
- Correlation Analysis:
  - Calculating correlations between numerical columns to see how they relate.

## Libraries Used

- pandas: For all data analysis tasks.

## Why This is Important

Univariate EDA is the first step in understanding your data. It helps you spot problems, understand distributions, and prepare for deeper analysis.

This folder is a practical guide to the basics of EDA in Python! 