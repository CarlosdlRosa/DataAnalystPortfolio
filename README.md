# Data Analyst Portfolio

## 1. Limpieza Project (Cleaning Data with SQL)

This project, titled Limpieza, is a comprehensive data cleaning exercise using SQL, focused on refining a dataset related to employee records. The original dataset, also named "Limpieza," contained inconsistencies, duplicates, and formatting issues such as incorrect date formats, non-standardized text entries, and missing values. Through this project, I demonstrate mastery of essential SQL skills, including data type conversion, handling duplicates, conditional transformations, and regular expressions.

### Project Overview

The **Limpieza Project** is designed to showcase advanced SQL techniques applied to real-world data challenges. The steps involved in the cleaning process include:

- **Data Import and Initial Setup**: The project begins by importing the dataset using the Table Data Import Wizard and setting up a safe environment for data modifications.
- **Column Standardization**: Column names were standardized to ensure consistency in language, casing, and character usage.
- **Duplicate Handling**: Duplicates were identified and removed by creating a temporary primary key and applying the `ROW_NUMBER` function to select the appropriate rows.
- **Whitespace Management**: Extra spaces within text fields were identified and trimmed, ensuring clean and uniform text data.
- **Translation and Transformation**: Non-English values were translated, and Boolean fields were converted from integer representations to more meaningful text descriptions.
- **Date Handling**: Dates were transformed into the standard `YYYY-MM-DD` format, and data types were adjusted accordingly.
- **New Columns**: Additional columns were generated to enhance the dataset, such as calculating employees' ages and generating email addresses based on existing data.
- **Data Export**: Finally, the cleaned data was reorganized and exported for further analysis.

### SQL Skills Demonstrated

This project highlights several key SQL skills, including but not limited to:

- **Data Type Conversion**: Effective use of `CAST`, `CONVERT`, and `ALTER TABLE` to manage and correct data types.
- **Handling Duplicates**: Using `ROW_NUMBER` and subqueries to identify and remove duplicate entries.
- **String Manipulation**: Utilizing functions like `TRIM`, `REPLACE`, and `CONCAT` to clean and standardize text data.
- **Conditional Logic**: Implementing `CASE` statements to transform data based on specific conditions.
- **Date and Time Functions**: Expertise in handling date formats and converting between date and text data types.

### Files

- [Original Dataset (.csv)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/Limpieza.csv)
- [SQL Code (.sql)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/limpieza.sql)
- [Cleaned Dataset (.csv)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/new_limpieza.csv)

This project underscores the importance of data cleaning as a critical step in any data analysis process. By systematically addressing the issues within the dataset, the **Limpieza Project** transforms raw data into a polished and ready-to-use form.

## 2. Cyclistic Case Study (Data Exploration for Business Solution with R)

This project, completed as the capstone project for the Google Data Analysis Certificate, explores the usage patterns of Cyclistic’s public bike service to develop strategies for maximizing annual memberships. The analysis focuses on identifying key differences between casual riders and annual members and proposing business solutions based on these insights.

### Project Overview

The **Cyclistic Membership Analysis** involved analyzing a dataset of bike trips to identify factors that could encourage casual users to become annual subscribers. The analysis includes:

- **Exploring Age and User Type**: Analyzed the distribution of user ages and compared statistics between casual and annual members to understand age-related patterns.
- **Examining Trip Duration**: Investigated how trip durations vary by user type to identify typical usage patterns and potential pricing strategies.
- **Correlation Between Age and Trip Duration**: Explored the relationship between user age and trip duration to find potential overlaps and opportunities for targeted marketing.

A detailed PowerPoint presentation was created to communicate the findings and recommendations for increasing annual memberships. The presentation includes visualizations and plots created using R.

### R Skills Demonstrated

This project showcases several R skills, including:

- **Data Manipulation**: Used `dplyr` functions like `group_by`, `summarize`, and `filter` to process and analyze the dataset.
- **Data Visualization**: Created visualizations using `ggplot2`, including `geom_boxplot` for age and trip duration distributions, and `geom_point` and `geom_jitter` for scatterplots analyzing age vs. trip duration.
- **Statistical Analysis**: Applied summary statistics functions such as `min`, `max`, `mean`, `median`, and `quantile` to understand data distribution.
- **Data Exploration for Business Solutions**: Employed data exploration techniques to generate actionable business insights, focusing on strategies to increase memberships based on user behavior.

### Files

- [Dataset (.zip)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/Cyclistic_Trips_2019_Q1.zip)
- [R Code (.R)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/Cyclistic_Trips_data_exploration.R)
- [PowerPoint Presentation (.pptx)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/Cyclistic%20case%20study%20presentation.pptx)

This project highlights the application of data analysis techniques to real-world business problems, demonstrating how data exploration can inform strategic decisions and drive organizational growth.

