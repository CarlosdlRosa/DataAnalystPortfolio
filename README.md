# Data Analyst Portfolio

## Index

1. [Limpieza Project (Cleaning Data with SQL)](#1-limpieza-project-cleaning-data-with-sql)
2. [Cyclistic Case Study (Data Exploration for Business Solution with R)](#2-cyclistic-case-study-data-exploration-for-business-solution-with-r)
3. [2021-2022 Premier League Season Analysis (Data Exploration and Transformation with Python)](#3-2021-2022-premier-league-season-analysis-data-exploration-and-transformation-with-python)
4. [HR Dashboard Visualization (Data Transformation and Visualization with Power BI)](#4-hr-dashboard-visualization-data-transformation-and-visualization-with-power-bi)

   
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

## 3. 2021-2022 Premier League Season Analysis (Data Exploration and Transformation with Python)

This project involves a detailed analysis of the 2021-2022 Premier League season, utilizing Python for data exploration and visualization. The dataset, which includes match results and statistics, was analyzed to uncover key insights into team performance, goal-scoring trends, and league standings.

### Project Overview

The **Premier League Season Analysis** focuses on examining various aspects of the season, including:

- **Goal Analysis**: Investigated whether more goals were scored by home or away teams, identified the top-performing home and away teams based on goals scored.
- **Second Halves Analysis**: Analyzed team performance in the second halves of matches, including which teams suffered the most comebacks, completed the most comebacks, and earned the most points.
- **Final League Standings**: Explored how many points each team earned by the end of the league and examined the standings at the end of each matchday, as well as created a new dataset with the final standings data from the pre-existing data of all the matches.
  
### Python Skills Demonstrated

This project showcases several key Python skills, including:

- **Data Loading and Exploring**: Leveraged `pandas` for loading and initial exploration of large datasets, including checking for null values and verifying dataset consistency with methods like `.info()`, `.columns`, and `.isnull()`.
- **Data Aggregation and Analysis**: Utilized `pandas` functions such as `.groupby()`, `.sum()`, and `.unique()` to aggregate data and analyze goals scored by home and away teams, including calculating averages and identifying top performers.
- **Advanced Data Manipulation**: Created and managed dictionaries to count and analyze complex metrics such as comebacks, second-half wins, and points earned, using Python's `iterrows()` for row-wise operations.
- **Custom Computations**: Developed custom algorithms to compute league standings and simulate each matchday standings, involving conditionals to assign points and generate standings dynamically.
- **Visualization**: Applied `matplotlib` and `seaborn` to create insightful visualizations of points earned in second halves, including bar plots and rotated x-axis labels for better readability.
- **Data Transformation and Export**: Constructed and refined a final dataset including detailed metrics such as goals scored, goals conceded, and win-loss records, and exported the final DataFrame to a CSV file for further use.

### Files

- [Original Dataset (.csv)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/Premier_League_2021-2022_Matches.csv)
- [Python Code (.ipynb)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/premier_league%20(english).ipynb)
- [Final Standings Dataset (.csv) – Generated from Exploration](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/Premier_League_21-22_Final_Standings.csv)

This project demonstrates how data analysis can provide valuable insights into sports performance and league dynamics, highlighting the application of Python for comprehensive data exploration and visualization.

## 4. HR Dashboard Visualization (Data Transformation and Visualization with Power BI)

This project builds on the cleaned data from the **Limpieza Project** and focuses on visualizing employee data through an interactive Power BI dashboard. The dashboard provides powerful insights on key HR metrics such as salaries, promotion-eligible employees, department headcount, and average salary by department. It demonstrates my ability to transform data using **Power Query**, create **calculated columns**, and apply **DAX** to deliver meaningful insights for Human Resources.

### Project Overview

The HR Dashboard was designed to support HR decision-making by presenting key employee data. Key steps involved include:

- **Data Import and Transformation**: Further cleaned and formatted the dataset using Power Query, including additional columns and merging data as needed.
- **Calculated Columns**: Created new columns to group employees by tenure, age brackets, and salary categories for deeper analysis.
- **DAX Measures**: Developed custom DAX measures to calculate metrics like average salary, employee turnover rate, and departmental performance.
- **Interactive Visualizations**: Built interactive visuals (bar charts, pie charts, line graphs) that allow users to explore specific demographics or departments.
- **HR-Specific Insights**: Delivered actionable insights into topics like salary distribution, potential promotion candidates, and department-wise employee breakdowns.

### Power BI Skills Demonstrated

This project highlights the following skills:

- **Data Transformation**: Extensive use of Power Query for data cleaning and transformation.
- **DAX Formulas**: Developed custom DAX measures to calculate HR-specific KPIs like salary averages and turnover rates.
- **Calculated Columns**: Generated new columns for age, salary brackets, and performance categorization.
- **Interactive Dashboards**: Designed an interactive dashboard that allows filtering and drill-down into HR metrics.
- **Data Visualization**: Created visuals like bar charts and pie charts to present data in a clear and accessible way.

### Files

- [Dataset (.csv)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/new_limpieza.csv)
- [Power BI Dashboard (.pbix)](https://github.com/CarlosdlRosa/PortfolioFiles/blob/main/Limpieza_HR_Dashboard.pbix)

### Conclusion

This project demonstrates how effective data visualization can provide valuable insights for HR decision-making. The HR Dashboard highlights my ability to transform raw data into actionable, interactive reports that support strategic decisions in Human Resources.
