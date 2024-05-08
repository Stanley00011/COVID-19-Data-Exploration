# COVID-19 Data Exploration Project

This project involves the exploration and analysis of COVID-19 data using SQL queries. The queries are designed to extract insights from COVID-19 datasets regarding total cases, total deaths, population percentages affected, infection rates, vaccination progress, and other related metrics.

## SQL Queries

### Data Retrieval Queries
1. **Query 1:** Retrieves all COVID-19 data entries where continent information is available, sorted by the third and fourth columns.
2. **Query 2:** Retrieves specific columns (Location, date, total_cases, new_cases, total_deaths, population) from COVID-19 data entries where continent information is available, sorted by location and date.
3. **Query 3:** Retrieves COVID-19 data entries for a specific location (e.g., Nigeria), calculating the death percentage based on total cases and total deaths.

### Data Analysis Queries
4. **Query 4:** Calculates the percentage of population infected with COVID-19 for each location, based on total cases and population.
5. **Query 5:** Identifies countries with the highest infection rates compared to their populations, showing the highest infection count and percentage of population infected.
6. **Query 6:** Shows the total cases, total deaths, and death percentage for each location, indicating the likelihood of dying if contracting COVID-19 in a specific country.
7. **Query 7:** Calculates the percentage of population vaccinated against COVID-19 over time, considering data from both COVID-19 deaths and vaccinations datasets.
8. **Query 8:** Uses Common Table Expressions (CTE) to perform calculations on vaccination data partitioned by location and date.
9. **Query 9:** Utilizes temporary tables to perform calculations on vaccination data partitioned by location and date.

### Views for Visualization
10. **View 1:** `PercentPopulationVaccinated` - Provides data for visualizing the percentage of population vaccinated against COVID-19 over time.
11. **View 2:** `PercentDeathsPerContinent` - Displays the total deaths and percentage of deaths per continent, based on available COVID-19 data.

## Usage

1. Clone the repository to your local machine.
2. Execute the SQL queries in your preferred SQL environment, ensuring connectivity to the relevant database.
3. Analyze the retrieved data and utilize the views for visualization purposes.

