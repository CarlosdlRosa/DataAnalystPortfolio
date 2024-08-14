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

## 2. Cyclistic Case Study (Maximizing Annual Memberships)

This project, titled **Cyclistic Case Study**, was conducted as the capstone project for the Google Data Analysis Certificate. The goal was to analyze the usage patterns of Cyclistic’s public bike service to develop strategies for increasing annual memberships. The analysis focused on identifying key differences between subscribers and casual riders, and proposing business solutions to optimize membership growth.

### Project Overview

The **Cyclistic Case Study** involved an in-depth exploration of bike usage data from the first quarter of 2019. Key aspects of the analysis included:

- **Age and User Type Analysis**: Explored the relationship between rider age and membership type to identify potential target demographics for subscription promotions.
- **Trip Duration Analysis**: Examined how trip duration varies between subscribers and casual riders to understand usage patterns and inform pricing strategies.
- **Relationship Between Age and Trip Duration**: Investigated how age impacts trip duration to uncover trends that could guide targeted marketing efforts.

### Key Insights

1. **Age Distribution**: Found that younger riders and those taking longer trips were more likely to be casual users, suggesting these groups as potential targets for discounted subscriptions.
2. **Trip Duration**: Identified that shorter trips were more common among subscribers, while casual users tended to take longer rides. This insight led to recommendations for adjusting pricing strategies to encourage casual riders to become subscribers.
3. **Combined Strategy**: Proposed a dual approach of offering discounts to younger users and increasing prices for long trips, aiming to convert casual riders into subscribers by addressing both their demographic and usage patterns.

### Skills Demonstrated

The project showcases a variety of data analysis skills, including:

- **Data Cleaning and Preparation**: Using R and `tidyverse` for initial data exploration and cleaning.
- **Exploratory Data Analysis (EDA)**: Utilizing summary statistics and visualizations to understand data distributions and relationships.
- **Visualization**: Creating informative plots using `ggplot2` to visualize age distribution, trip duration, and their relationship.
- **Hypothesis Testing**: Formulating and testing hypotheses about user behavior to drive business recommendations.

### Files

- [Dataset (.csv)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/Cyclistic_Trips_2019_Q1.csv)
- [R Code (.R)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/cyclistic_analysis.R)
- [Presentation (.pptx)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/Cyclistic_Case_Study_Presentation.pptx)

This project demonstrates the application of data analysis techniques to real-world business problems, offering actionable insights for maximizing annual memberships and improving service offerings.
