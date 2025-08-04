# airlines-flight-data-cleaning
Data Cleaning and Preprocessing of Airlines Flight Dataset using Python (Pandas) - Handling missing values, duplicates, text formatting, date standardization, and data type corrections.
Airlines Flight Data Cleaning Project

This project contains a workflow for cleaning and preprocessing an Airlines Flight Dataset using Python and Pandas. It includes tasks like handling missing values, removing duplicates, fixing inconsistent formats, and preparing the data for analysis or machine learning.

Dataset Used:
Airlines Flight Dataset (Flight delays and cancellations from Kaggle or other sources) containing missing values, duplicate records, inconsistent text formats, and unclean date fields.

Data Cleaning Steps Performed:

Handling missing values using isnull(), fillna(), dropna()

Removing duplicate records using drop_duplicates()

Standardizing text columns (Airline Names, Airport Codes)

Converting date columns to dd-mm-yyyy format

Renaming column headers to snake_case format

Fixing data types (integers, floats, date-times)

Outlier treatment (optional)

Tools & Libraries Used:
Python 3.x
Pandas Library
Google Colab or Jupyter Notebook
CSV file handling

Project Files:
flights_cleaned.csv – Final cleaned dataset
flight_data_cleaning.ipynb – Python notebook with data cleaning code
README.md – Project documentation

How to Use:
Clone or download this repository.
Open flight_data_cleaning.ipynb in Google Colab or Jupyter Notebook.
Upload your raw dataset (flights.csv) into Colab.
Run the notebook cells to clean the data.
The cleaned dataset will be saved as flights_cleaned.csv.
