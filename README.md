# COVID-19 Data Analysis with SQL and Tableau

---

## **Project Name**: COVID-19 Data Analysis and Visualizations

---

### **Objective**:
This project focuses on analyzing COVID-19 data to extract key insights regarding cases, deaths, and vaccinations across the world. SQL is used to query, process, and aggregate the data, while Tableau is utilized for creating interactive visualizations that help identify trends and patterns. The primary goal is to visualize the spread and impact of COVID-19 across countries and continents, as well as forecast future trends using the available data.

---

### **Table of Contents**

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [SQL Analysis](#sql-analysis)
4. [Visualizations in Tableau](#visualizations-in-tableau)
5. [Key Insights](#key-insights)
6. [How to Use](#how-to-use)
7. [Conclusion](#conclusion)

---

## **Introduction**:
This project explores the COVID-19 pandemic's progression globally by analyzing key metrics like total cases, deaths, and vaccinations. SQL is used to retrieve, calculate, and analyze data from multiple tables, while Tableau provides a platform for visualizing this information interactively. The analysis focuses on understanding trends in infection rates, death rates, and vaccination progress at both country and continent levels.

---

## **Dataset**:
- **Source**:  Covid-19 Global data is taken from https://ourworldindata.org/covid-deaths
---

## **SQL Analysis**:

Several SQL queries were used to gather meaningful insights from the data. Here's an overview of the key queries used:

1. **Global Cases and Deaths**:
   - Calculates the total number of cases, deaths, and the death percentage globally. This helps identify the overall global impact of COVID-19.

2. **Total Deaths vs Total Cases**:
   - Compares the number of total deaths against total cases on a country-by-country basis, helping visualize which countries were hardest hit in terms of mortality.

3. **Total Cases vs Population**:
   - Calculates the percentage of each country's population that has been infected by COVID-19, showing the relative spread of the virus within different nations.

4. **Countries with the Highest Infection Rate**:
   - Finds the countries with the highest infection rates by comparing the total cases against the population.

5. **Countries with the Highest Deaths**:
   - Lists the countries with the highest number of deaths, identifying the nations that faced the greatest loss of life due to COVID-19.

6. **Vaccination Progress**:
   - Tracks the running total of vaccinations in each country, allowing us to follow vaccination progress over time.

7. **Percent of Population Vaccinated**:
   - Compares the running total of vaccinations with the population size, calculating the percentage of the population vaccinated for each country.

---

## **Visualizations in Tableau**:
The following four key visualizations were created in Tableau based on the SQL queries:

1. **Global Numbers of Cases and Deaths**:
   - Displays the total global cases and deaths, helping identify the regions most impacted by the pandemic. A world map and bar chart are used to represent the data.

     ![Screenshot 2024-09-06 144723](https://github.com/user-attachments/assets/c9b645b2-c62c-4ae8-a298-2a29c83c8e19)


2. **Percent Population Infected per Country**:
   - Visualizes the percentage of each country’s population that has been infected with COVID-19, ranking countries based on infection rates.
     ![Screenshot 2024-09-06 143800](https://github.com/user-attachments/assets/f5322ae4-ff04-4896-b28e-0242a35aaa56)
     ![Screenshot 2024-09-06 144331](https://github.com/user-attachments/assets/e7102a06-285d-4cf5-9c54-c84d3805229b)
     ![Screenshot 2024-09-06 143646](https://github.com/user-attachments/assets/c781d649-d50d-4888-9ff1-a5ae9798fd3a)


3. **Total Death Count vs Continent**:
   - Compares the total death count for each continent, helping to identify which regions suffered the most fatalities relative to others.
     ![Screenshot 2024-09-06 143418](https://github.com/user-attachments/assets/46099af8-06b1-47cf-aa26-11701418c6d9)

4. **Forecasting Percent Population Infected**:
   - A forecasting chart that projects the percentage of the population infected with COVID-19, based on current trends. This helps predict future infection rates for various countries.
     ![Screenshot 2024-09-06 143346](https://github.com/user-attachments/assets/316c5195-e5b1-4932-bfca-2360ec00af26)


---

## **Key Insights**:
- **Global Impact**: Major countries like the United States, Brazil, and India recorded the highest infection and death counts.
- **Infection Rates**: Smaller nations or those with higher population densities often had higher relative infection rates.
- **Vaccination Progress**: Some countries made rapid progress in vaccinating their populations, while others lagged behind.
- **Continental Comparison**: Europe and South America witnessed higher death counts, reflecting the severe impact COVID-19 had on those continents.
- **Forecast**: The forecasting model predicts continued infection growth in certain countries, but also highlights regions where the spread is expected to slow.

---

## **How to Use**:

1. **SQL Analysis**:
   - Run the SQL queries on a database containing the `CovidDeaths` and `CovidVaccinations` tables to analyze the COVID-19 data.

2. **Tableau Visualizations**:
   - Download the provided Tableau workbook (`.twbx` file) and open it using **Tableau Desktop**.
   - Tableau Desktop is required to view the visualizations. Once opened, you can interact with the dashboards, apply filters (e.g., country, date), and explore various aspects of the data.

---

## **Conclusion**:
This project offers a comprehensive analysis of COVID-19 cases, deaths, and vaccinations globally. By leveraging SQL to extract and process the data, and Tableau for visualization, it provides valuable insights into the pandemic's trends and patterns. The visualizations highlight the global and regional impact of COVID-19, helping to understand the spread of the virus and vaccination progress.
