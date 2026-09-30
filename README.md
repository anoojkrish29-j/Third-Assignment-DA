# Third-Assignment-DA
## Assignment 3 - Module evaluation
### Data Cleaning

1) Check for the number of missing values marked with '?' in each column of the “Medical Examinations” Table and "Hospitalization Details" Table.
 
 - Ans: 15 missing ,used find.
2) Fill in the missing values of ‘month’ with Sep and ‘year’ with its average rounded to the nearest integer.
  
 - Ans: Found using find and filled month using Sep and Year with most occurring values average using mode and Find & replace.
3) Determine the most frequently occurring values in the ‘smoker’, 'Hospital tier' and 'City tier' columns, and fill in the missing values accordingly.
 
 - Ans:Filled the rows using Mode, find and replace
4) If any 'State ID' values are missing, consider filling them with 'Unknown' or using another appropriate strategy.

-  Ans: 2 missing field marked with unknown.

### Data Transformation.

1) Split the ‘names’ column in the “Customer Names” Table into 3 meaningful columns: ‘Title’, ‘First Name’, and ‘Last Name’.
 
 - Ans:Used Textafter() and Textbefore().
2) Convert the "NumberOfMajorSurgeries" column in the “Medical Examinations” Table to
numerical data by replacing non-numeric characters with meaningful numerical values.
 
 - Ans: Replaced non numeric to 0 using if().
3) Check for inconsistencies in the 'Heart Issues' and 'smoker' columns and propose
corrective actions if necessary.
 
  - Ans: using proper() corrected inconsistencies.
4) Create a new column named “Weight Status” that categorizes BMI into different
categories as below:
 
 - Ans: created a new column and categorized using IFS()
5) Create a new column named “Diabetes Status” and fill it as per the information given
below:
  
 - Ans:created a new column and categorized using IFS()
6) Merge ‘year’, ‘month’ and ‘date’ columns in the “Hospitalization Details” Table into one
column named ‘Date of Birth’ and format it in ‘DD-MMM-YYYY’ custom format.
 
-  Ans:Used Date() and merged.
7) Calculate the ‘Age’ of each customer based on their ‘Date of Birth’ and the date of
collection of the dataset, which is 8thJune 2023.
  
 - Ans: Found Age using Datedif()
8) Format ‘charges’ column as currency ($).
 
-  Ans: Changed to currency format

### Data Exploration, Analysis & Visualization:
- Created a new sheet named Health Care and transferred data from all the sheets using vlookup().


- Created Pivot tables using Cancer History among Smokers and Non-Smokers, also with Total number of major surgeries and average HBA1C differ between patients with and without a history of transplants. Created Pie/Doughnut charts with the Pivot table data.
- Created Column/Bar Chart, using healthcare charges vary based on different weight statuses and diabetes statuses and average charges for each hospital tier within different states.

- Created Line/Scatter Plot, using correlation between Age and both BMI and HBA1C and relationship between Age and Healthcare charges.

- Built a Dash Board sheet that brings all charts together.
- Slicer added for Weight Status and Diabetes Status, connected to the pivot tables, to filter the visualizations and compare health outcomes and charges.


