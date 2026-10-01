# data-science-python-foundations

# Employee Data Analysis from PDF

## Project Overview

This project demonstrates an end-to-end data analysis workflow using Python.

The employee dataset was provided in PDF format. Tables were extracted from the PDF, combined into a single dataset, cleaned, analyzed, visualized, and used to generate business insights.

## Project Objectives

* Extract tabular data from a PDF
* Combine multiple tables into a single DataFrame
* Identify and handle missing values
* Check for duplicate records
* Validate data types and data quality
* Perform statistical analysis using NumPy
* Perform data manipulation and analysis using Pandas
* Perform Exploratory Data Analysis (EDA)
* Create visualizations
* Identify useful business insights

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Tabula
* Jupyter Notebook

## Project Workflow

```text
PDF
 ↓
Table Extraction using Tabula
 ↓
Combine Tables using Pandas
 ↓
Data Cleaning
 ↓
Missing Value Treatment
 ↓
Duplicate & Data Quality Checks
 ↓
NumPy Analysis
 ↓
Pandas Analysis
 ↓
Exploratory Data Analysis
 ↓
Data Visualization
 ↓
Business Insights
```

## Data Cleaning

The dataset was checked for:

* Missing values
* Duplicate records
* Incorrect data types
* Invalid values

Missing values were handled using appropriate techniques depending on the type of variable.

For example:

* Numerical variables → mean or median imputation
* Categorical variables → mode imputation

## Analysis Performed

The project includes:

* Descriptive statistics
* Mean, median, standard deviation
* Percentiles
* GroupBy analysis
* Aggregations
* Sorting and filtering
* Correlation analysis
* Salary analysis
* Department-wise analysis
* City-wise analysis
* Employee performance analysis

## Exploratory Data Analysis

EDA was performed to understand:

* Employee distribution across departments
* Salary distribution
* Experience and salary relationship
* Performance and salary relationship
* Salary differences across cities
* Potential salary outliers

## Visualizations

The project includes visualizations such as:

* Salary distribution histogram
* Department-wise salary comparison
* Employee count by department
* Experience vs Salary scatter plot
* Performance vs Salary scatter plot
* Salary boxplot

## Business Insights

The analysis was used to identify patterns related to:

* Average salary
* Department-wise salary
* Employee distribution
* City-wise salary
* Experience and salary
* Performance and salary
* Salary outliers

## Project Structure

```text
data-science-python-foundations/
│
├── data/
│   ├── raw/
│   │   └── employee_report.pdf
│   │
│   └── processed/
│       └── employee_cleaned.csv
│
├── notebooks/
│   └── employee_pdf_analysis.ipynb
│
├── .gitignore
├── README.md
└── requirements.txt
```

## Conclusion

This project demonstrates a complete data analysis workflow, starting from raw PDF data extraction and continuing through data cleaning, statistical analysis, exploratory data analysis, visualization, and business insights.

The project provides practical experience with Python, NumPy, Pandas, data visualization, and real-world data preprocessing.
