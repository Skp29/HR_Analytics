# HR Analytics Project

## Project Overview

This project focuses on analyzing human resource data to gain insights into employee attrition, performance, and satisfaction across various departments and roles within a company. By employing data cleaning, manipulation, and visualization techniques, we aim to uncover underlying patterns that could inform decision-making processes to improve employee retention and performance.

## Dataset

The dataset `hr.csv` includes information on employees' age, attrition status, department, job role, monthly income, and other related attributes.

## Technical Aspects

The analysis was conducted using Python and MySQL. Python's data manipulation capabilities were harnessed using libraries such as Pandas and NumPy, while Seaborn and Matplotlib were utilized for data visualization.

### Data Cleaning

Data cleaning steps involved:

- Deleting redundant columns
- Renaming the columns for better readability
- Dropping duplicates to ensure data integrity
- Handling NaN values appropriately
- Additional data transformations for analysis readiness

### MySQL Database

The cleaned data was then uploaded to a MySQL database, allowing for structured data storage and the use of SQL queries for further analysis.

## Data Visualization

Six different types of data visualizations were created to analyze the dataset:

1. **Average Monthly Income by Job Role**: A bar plot to observe the mean monthly income across different job roles.
2. *(Five more visualizations as per the project...)*
   
## Installation and Usage

Before running the scripts, please set up the following environment variables for your MySQL connection:
- `MYSQL_USER`: Your MySQL username
- `MYSQL_PASSWORD`: Your MySQL password

Replace these in the code with your actual username and password. For enhanced security, it's recommended to use a configuration file or environment variables that are not tracked in your version control system.


## Contributing

We welcome contributions and suggestions! Please fork the repository and create a new pull request for review.


---

This `README` is a general guide—please ensure that each section accurately reflects the specifics of your project. Adjust and add to it as necessary to provide the best context for your HR Analytics project.
