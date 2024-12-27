# NYC Flights Analysis - Assignment 3

## Introduction
This repository contains a Jupyter Notebook for **Intro to Data Science - Assignment 3**. The notebook demonstrates various data analysis techniques using Python and Pandas on a dataset of New York City flights.

## Dataset
The analysis is based on the `nycflights.csv` dataset, which contains detailed information about flight departures and arrivals from NYC.

## Notebook Contents
The notebook is structured as follows:

### Questions and Analysis
1. **Data Loading and Selection**
   - Loaded the `nycflights.csv` dataset into a Pandas DataFrame.
   - Created a new DataFrame `newyork_flight_new` with selected columns: `dep_time`, `dep_delay`, `arr_time`, `arr_delay`, and `tailnum`.

2. **Filtering Rows Based on Conditions**
   - Filtered rows with departure times greater than 2000 and calculated the number of deleted rows.

3. **Handling Missing Values**
   - Checked for missing values in the `dep_delay` column.
   - Replaced missing values with the median of `dep_delay`.

4. **Querying the Data**
   - Used the `query` function to filter rows where `airtime > 120` minutes and `distance > 700` km.

5. **Data Transformation**
   - Created a new DataFrame using `filter()` to include additional flight details such as destination.

### Techniques Used
- Data Cleaning: Handling missing values and filtering rows.
- Data Transformation: Creating new DataFrames and applying filters.
- Descriptive Statistics: Calculating medians and summarizing data.

## How to Run
1. Clone this repository:
   ```bash
   https://github.com/vineeth2707/-NYC-FlightData-Analysis-and-Linear-Regression-Modeling/blob/main/NYC_Flights_Data_Analysis_and_Linear_Regression_Modeling.ipynb
   ```
2. Navigate to the directory:
   ```bash
   cd nyc-flights-analysis
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   NYC Flights Data Analysis and Linear Regression Modeling.ipynb
   ```

## Requirements
- Python 3.x
- Pandas
- Jupyter Notebook

## Acknowledgments
This notebook was created as part of the **Intro to Data Science** coursework.

## License
This project is licensed under the MIT License. 

