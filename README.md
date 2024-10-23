# Employee-Registration-Process-Using-DevOps


Introduction
This program is an Employee Registration Process tool implemented in Python using pandas and matplotlib. It allows users to perform various operations on employee data, including CRUD (Create, Read, Update, Delete) operations, finding statistical relations, performing basic dataframe operations, and visualizing data through various types of charts.

Features
The program offers the following major functionalities:

1. CRUD Operations
Create: Add new rows or columns to the employee data.

Read: View the entire dataset or specific rows and columns.

Update: Modify existing rows or columns.

Delete: Remove rows or columns from the dataset.
3. Finding Relations
Correlation: Measure the correlation between employee attributes such as Age, Experience, and ID.

Covariance: Calculate the covariance between different employee attributes.
4. Basic DataFrame Operations
Describe: Get statistical summaries (mean, standard deviation, etc.) of the dataset.

Info: View metadata about the dataframe, such as column types and non-null values.

Head/Tail: Display the first or last few rows of the dataset.

Rank: Rank the data based on the values of specific columns.

Filter: Filter the dataset based on specific columns.

GroupBy: Group the data based on certain columns.

Aggregate: Apply aggregate functions like sum, min, max, and count.
5. Data Visualization
Univariate Analysis: Visualize data of a single attribute (e.g., Employee Experience).

Bivariate Analysis: Plot the relationship between two attributes (e.g., Employee Age vs. Employee ID).

Multivariate Analysis: Compare multiple attributes (e.g., Employee Age and Salary).

Scatter Plot: Create scatter plots to view correlations between attributes.

Bar Graph (Vertical and Horizontal): Visualize categorical data using bar graphs.

Pie Chart: Show the distribution of employee IDs by employee names.
Data Structure
The employee dataset is stored in a pandas DataFrame and contains the following columns:

Emp Id: Unique employee identifier.
Emp Name: Employee's name.
Emp Age: Employee's age.
Emp Email: Employee's email address.
Emp Phone No: Employee's contact number.
Emp Gender: Employee's gender.
Emp Address: Employee's residential address.
Emp City: City where the employee resides.
Emp Pincode: Employee's postal code.
Emp Qualification: Employee's highest qualification.
Emp Experience: Number of years of work experience.
Emp Type: Employment type (Freelancer, Permanent, Temporary).
Emp Salary: Employee's salary.
Emp Work Mode: Mode of work (On Site, Work From Home, Hybrid, etc.).
Emp Marital Status: Marital status (Married, Unmarried).
Emp Role: Employee's role in the organization.
DataFrame Indexing
The employees are indexed as Emp1, Emp2, etc., for easy reference.

Usage Instructions
Run the program: Execute the script in a Python environment.

Choose an operation: The program prompts the user to select one of the following main operations:

CRUD operations
Finding Relations (Correlation/Covariance)
Basic DataFrame Operations (e.g., describe, filter, group by)
Data Visualization (e.g., bar charts, pie charts)
Exit
Enter the appropriate option: Based on the operation chosen, follow the prompts to perform tasks like adding a new row, reading specific columns, updating rows, calculating correlations, or visualizing data.

Exit the program: Select "Exit" from the menu to terminate the process.

Libraries Used
pandas: For handling and manipulating tabular data.
matplotlib.pyplot: For visualizing the data.
Example Commands
To add a new employee row, choose 1 for CRUD operations, then 1 to Create, and follow the prompts.
To view the correlation between employee IDs and experience, choose 2 for Finding Relations and then select Correlation.
To visualize a bar chart comparing Employee Experience with Salary, choose 4 for Data Visualization, and then 5 for Bar Graph.
Conclusion
This Employee Registration Process tool provides an interactive way to manage employee data, perform essential analytics, and generate visual reports. It's useful for HR managers or anyone handling employee records in small to medium-sized organizations.
