**Weather Data Analysis README Manual**

**Overview**
This Python script analyzes weather data using various statistical techniques including data cleaning, correlation analysis, and linear regression. It employs libraries such as Pandas, NumPy, and SciPy for data manipulation and analysis.

**Requirements**
Python 3.x
Pandas
NumPy
SciPy

**Installation** 
Install Python from python.org.
Install required packages using pip:
pip install pandas numpy scipy

**Usage**
1.Data Preparation and Analysis
- Open the Python script.
- Modify the Google Sheets URL to your weather dataset.
- Run the script to clean and preprocess the data.
- The script performs correlation analysis and linear regression to identify relationships between weather parameters.

2.Interpreting Results
- The script prints correlation matrices between weather parameters.
- It computes linear regression models to predict target variables based on specified features.
- Results are printed in the console for interpretation.

3.Handling Warnings
- The script may trigger a FutureWarning due to changes in Pandas default behavior.
- Modify the correlation computation to include numeric_only=True explicitly to avoid this warning.

**Contributors**
[Samay Mehar/samay2504] - Initial author

**License**
This project is licensed under the MIT License.

