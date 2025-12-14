# Data-Analysis-Warmup-Exercise
# Data Analysis Warmup Exercise

This notebook contains a basic data analysis exercise using Python and pandas to explore a small dataset of student information.

## Dataset Overview
The dataset contains three columns:
- **Name**: Student names
- **Marks**: Student marks (scores)
- **Gender**: Student gender (Male/Female)

## Notebook Contents
The notebook demonstrates fundamental pandas operations including:

1. **Data Loading**: Creating a DataFrame from a Python dictionary
2. **Data Inspection**:
   - Displaying top and bottom rows
   - Checking dataset shape (rows and columns)
   - Getting data types and memory usage
   - Finding null values
   - Generating descriptive statistics

3. **Data Analysis**:
   - Finding unique values and value counts
   - Filtering data using conditions
   - Calculating summary statistics (mean, count)
   - Applying functions to columns
   - Using map functions for value transformation

4. **Data Manipulation**:
   - Adding new columns
   - Dropping columns
   - Sorting data by values
   - Selecting specific columns

5. **Basic Operations**:
   - Accessing column names
   - Working with indexes
   - Conditional filtering (e.g., female students with marks ≥ 90)

## Key Functions Demonstrated
- `df.head()`, `df.tail()` - Viewing data
- `df.shape` - Dataset dimensions
- `df.info()` - Data structure information
- `df.describe()` - Statistical summary
- `df.isnull().sum()` - Missing value detection
- `df['column'].unique()`, `df['column'].nunique()` - Unique value analysis
- `df['column'].value_counts()` - Frequency counts
- `df['column'].between()` - Range filtering
- `df['column'].mean()` - Average calculation
- `df.apply()` - Function application
- `df.map()` - Value mapping
- `df.drop()` - Column removal
- `df.sort_values()` - Data sorting
- Boolean indexing for filtering

## Requirements
- Python 3.x
- pandas library

## Usage
This notebook serves as a warmup exercise for beginners learning pandas data manipulation and analysis. Each cell demonstrates a specific pandas operation with clear outputs.
