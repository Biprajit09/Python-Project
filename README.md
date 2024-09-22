# 📊 Python Project

## Executive Summary
This project showcases my data manipulation and analysis skills using Python, specifically with Pandas and NumPy. The goal was to manage and analyze employee and project data, addressing various tasks to demonstrate proficiency in data cleaning, transformation, and integration.

## 💡 Key Skills Demonstrated
- **Data Manipulation**: Used Pandas for creating and modifying dataframes, handling missing values, and merging datasets.
- **Data Cleaning**: Replaced missing values using techniques like running averages and transformed data for analysis.
- **Data Transformation**: Performed operations like splitting columns, dropping unnecessary data, and adding new calculated fields.
- **Conditional Logic**: Applied conditional statements to update records based on specific criteria, enhancing data accuracy.
- **Data Aggregation**: Calculated totals and grouped data effectively to generate insightful summaries.

## 📄 Dataset Explanations
### Attributes
1. **id** - Assigned number for the project head.
2. **name** - Person handling the project.
3. **gender** – Male (M), Female (F).
4. **city** - Locations of the project.
5. **age** - Number of years the project will be active.
6. **status** - Status of the project.
7. **designation level** - Position of the project head, with specific rules for promotions and demotions.

### DataFrames
1. **Employee DataFrame**: Contains employee information such as ID, Name, Gender, City, and Age.
2. **Seniority Level DataFrame**: Contains the designation levels of employees.
3. **Project DataFrame**: Contains project details including ID, Project Name, Cost, and Status.

## 🛠️ Tasks Overview
The project consists of the following tasks:
1. Created three dataframes and saved them as CSV files.
2. Handled missing values in the Project Cost column using running averages.
3. Split the Name column into First Name and Last Name.
4. Joined all three dataframes into one consolidated dataframe named "Final."
5. Added a bonus column based on project completion status.
6. Demoted designation levels for employees with failed projects and removed those exceeding level 4.
7. Added titles to names and removed the Gender column.
8. Promoted employees older than 29 years.
9. Created a new dataframe to sum project costs by employee.
10. Filtered and printed employee details based on city names containing the letter "o."

## 🖥️ Technologies Used
- **Python**: Core programming language for data manipulation.
- **Pandas**: Library used for data manipulation and analysis.
- **NumPy**: Library used for numerical operations and handling arrays.

