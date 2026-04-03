## Finance_Analysis
#My data analysis assignments on finance using Google Colab.

📊 Finance Analysis Project

  Overview

This project performs data analysis and visualization on a financial transactions dataset using Python. It focuses on cleaning the data, exploring key metrics, and generating insights through charts.

The notebook walks through a complete data analysis workflow:

 Data loading
 Data cleaning
 Exploratory Data Analysis (EDA)
 Visualization

   Summary insights

Tools & Libraries

The project uses the following Python libraries:

 "pandas" for data manipulation and analysis
 "numpy" for numerical operations
 "matplotlib" for data visualization
 "openpyxl" for reading Excel files



 Dataset

The dataset used is:

finance_transactions_dataset.xlsx

It contains financial transaction records with fields such as:

 Amount,
 Net Amount,
 Tax Amount,
 Transaction Type,
 Transaction Date,
 Approval Status,
 Company, Department, Analyst,
 Sector, Category, Currency



 Project Workflow

1. Data Loading

 The dataset is loaded using "pandas.read_excel()"
 Basic structure is inspected ("shape", "columns", "info")

2. Data Cleaning

 Missing values handled:
   Critical columns and rows dropped.
   Text fields and filled with ""Unknown"".
 Date column converted to proper datetime format.
 Duplicates removed.

3. Data Exploration

 Summary statistics generated using:
   "describe()"
   "isnull().sum()"

4. Data Visualization

Several charts are created to uncover insights:

 Bar Chart
  Total amount by transaction type

 Grouped Bar Chart
  Net amount vs tax amount by sector

 Line Chart
  Monthly transaction trends

 Pie Chart
  Approval status distribution

 Horizontal Bar Chart
  Top analysts by transaction amount

  Additional analyses: 
 1. Currency distribution
 2. Department averages
 3. Expense categories
 4. Transaction type breakdown

5. Summary Output

The notebook prints a financial summary including:

1. Total transactions
2. Total amount
3. Total tax paid



 Key Insights

This analysis helps to:

1. Understand spending patterns
2. Track monthly financial performance
3. Compare tax vs net revenue
4. Identify top-performing analysts
5. Analyze approval trends

