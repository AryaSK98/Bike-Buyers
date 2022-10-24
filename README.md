## Bike Buyers - Data Cleaning and Dashboard Creation
This project focuses on data cleaning and creating dashboard in Excel.
### About Dataset
*	The dataset contains information about customers, gender, income, marital status, education, occupation, age, whether they purchased a bike or not, etc…
*	Each record is identified by a unique id.
*	The data is stored in 1026 rows and 13 columns, alongwith a header row.
### Data Cleaning Process
*	Created a copy of the raw data in a new worksheet called ‘Working Sheet’.
*	Row height and column width are adjusted.
*	Removed duplicates – found 26 duplicates; all are removed which reduced the number of rows to 1000.
*	Replaced ‘M’ and ‘S’ in column ‘Marital Status’ with ‘Married’ and ‘Single’, respectively.
*	Replaced ‘M’ and ‘F’ in column ‘Gender’ with ‘Male’ and ‘Female’, respectively.
*	Created a new column called ‘Age Brackets’ to categorize the customers to following groups according to their age:  
  a. ‘<31’ – Adolescent  
  b. ’31 – 54’ – Middle Age  
  c. ‘>54’ – Old  
*	Converted the data rage into a table and named it ‘Bike_Buyers’.
### Analysis and Visualization
*	Created a new worksheet named ‘Pivot Tables’.
*	Analysed the data with the help of 4 pivot tables:  
  a. Percentage of customers who bought and didn't buy a bike  
  b. Average income of customers by gender  
  c. Commute distance of customers  
  d. Age group of customers  
* All pivot tables compared the number of buyers and non-buyers.
*	Charts were created to visualize the information in them.
### Dashboard Creation
*	Created a new worksheet named ‘Dashboard’.
*	Copied the created charts to this worksheet.
*	Resized the charts.
*	Created slicers for ‘Marital Status’, ‘Region’, ‘Education’ and 'Occupation', and connected it to all the charts.
*	Added heading and changed the background.
