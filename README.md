# Covid-19 Data Exploration

This project explores Covid-19 data using SQL queries, focusing on various metrics such as total cases, deaths, infection rates, and vaccination progress across different countries and continents. The analysis includes several SQL concepts such as joins, common table expressions (CTEs), temporary tables, window functions, aggregate functions, views, and data type conversions.

## Project Structure

The project is structured around several key SQL queries that analyze and visualize the impact of Covid-19 across different regions. Below is a breakdown of the main sections and SQL operations used:

1. **Initial Data Exploration**
   - Filtering data by continent to focus on relevant locations.
   - Ordering data by location and date to observe trends.

2. **Total Cases vs Total Deaths**
   - Calculates the likelihood of dying if infected by Covid-19 in different countries, with a specific focus on Brazil.

3. **Total Cases vs Population**
   - Analyzes the percentage of the population infected with Covid-19 in Brazil.

4. **Countries with Highest Infection Rate**
   - Identifies countries with the highest infection rates relative to their population.

5. **Countries with Highest Death Count per Population**
   - Ranks countries based on their total death count, normalized by population.

6. **Continental Analysis**
   - Aggregates data to compare the total death count per population across continents.

7. **Global Metrics**
   - Summarizes global totals for cases, deaths, and death percentages.

8. **Total Population vs Vaccinations**
   - Shows the percentage of the population that has received at least one Covid-19 vaccine.

9. **Using CTEs and Temp Tables**
   - Demonstrates how to use Common Table Expressions (CTEs) and temporary tables to calculate and partition data for more complex analysis.

10. **Creating Views for Data Visualization**
    - Creates a SQL view to store data for later visualization and reporting.

## SQL Concepts Used

- **Joins**: Combining data from multiple tables (CovidDeaths and CovidVax).
- **CTEs**: Simplifying complex queries by breaking them into more manageable parts.
- **Temp Tables**: Storing intermediate results for repeated use.
- **Window Functions**: Calculating running totals and percentages.
- **Aggregate Functions**: Summing and averaging data to gain insights.
- **Views**: Creating a stored query for easy access to processed data.
- **Data Type Conversions**: Ensuring accurate calculations and compatibility across different data types.
