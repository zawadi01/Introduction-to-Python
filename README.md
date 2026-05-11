# Introduction-to-Python
Working with a synthetic dataset and API Endpoints.

# Project: Student Data Processing

## Overview
This project demonstrates how to retrieve and process student data from a remote JSON file using Python, `requests` and `pandas`.

## Data Source
The raw student data is sourced from a GitHub repository:
`https://raw.githubusercontent.com/zawadi01/supermarketdata/refs/heads/main/MOCK_DATA%20(1).json`

## Steps Performed

1.  **Import Libraries**: Imported `requests` for fetching data and `pandas` for data manipulation.
2.  **Fetch Data**: Downloaded the JSON data from the specified URL.
3.  **Status Check**: Verified the successful retrieval of data by checking the HTTP status code (expected `200`).
4.  **Parse JSON**: Converted the raw JSON response into a Python list of dictionaries.
5.  **Create DataFrame**: Transformed the list of dictionaries into a pandas DataFrame.
6.  **Save to CSV**: Stored the processed DataFrame as a CSV file named `students_data.csv`.
7.  **Display Data**: Displayed the first few rows of the DataFrame to confirm successful processing.

## Files
-   `students_data.csv`: The processed student data in CSV format.

## How to Use
To replicate the steps:
1.  Run the Python cells in the notebook sequentially.
2.  The `students_data.csv` file will be generated in your Colab environment.

Perform the same operations for the dummy JSON data as an API. Follow the steps in the 'Working with API Endpoints' file.
