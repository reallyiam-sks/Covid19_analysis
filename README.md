# COVID-19 Data Exploration Project (SQL Portfolio Project)

This project is inspired by Alex The Analyst’s Data Analyst Portfolio Project Series. It focuses on data exploration using SQL to uncover insights from global COVID-19 data. The dataset includes detailed statistics on cases, deaths, and vaccinations gathered from Our World in Data.
The project demonstrates SQL skills such as joins, aggregate functions, casting, temporary tables, common table expressions (CTEs), and view creation—forming the foundation for data analysis and visualization (later extended to Tableau).

## Project Overview

### The analysis explores:

* Global and country-level trends in COVID-19 cases, deaths, and vaccination rates.

* Death percentage relative to total cases.

* Infection percentage relative to population.

* Countries with the highest infection and death rates.

* Global death statistics over time.

This repository focuses on SQL data exploration, the first part of a 4-step portfolio progression:

* SQL Data Exploration

* Tableau Visualization

* Advanced SQL ETL and Cleaning

### Tools & Technologies Used
* SQL Server Management Studio (SSMS)

* Microsoft SQL Server 2019

* Excel

* Tableau (for upcoming visualization project)

* GitHub (for version control and documentation)

### Datasets
* COVID-19 Deaths Data

* COVID-19 Vaccinations Data

Both datasets are sourced from Our World in Data and include information such as:

location, date, total_cases, new_cases, total_deaths, population

new_vaccinations, total_vaccinations, people_vaccinated

### Objectives & Key Queries
1. Basic Exploration
   Preview the data.
   Understand the schema and data types.
   Clean columns and prepare for joins.

2. Death Percentage by Country

3. Infection Rate vs Population

4. Highest Infection Rate per Country

5. Countries with Highest Death Count

6. Global Numbers Over Time

7. Joining Death and Vaccination Tables

### Insights
Global death rate stabilizes around 2% after 2021.

Small countries with limited population show very high infection percentages.

The United States and India consistently rank among top countries in total cases and deaths.

Europe recorded higher infection penetration due to early outbreaks and population density.

### SQL Concepts Demonstrated
Filtering data with clauses (WHERE, GROUP BY, ORDER BY)

Data type handling (CAST, CONVERT)

Aggregate functions (SUM, MAX, AVG)

Joins across multiple datasets

Temporary tables and CTEs for intermediate processing

Creating views for reporting and visualization integration with Tableau


### Next Steps
Use the SQL queries to create views for Tableau visualization.

Create dashboards showing:

Global infection and death trends.

Vaccination progress by continent.

Comparative charts of infection rates across countries.

Upload visualizations as part of Project 2.

