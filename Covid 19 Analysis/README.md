**COVID-19 Data Analysis Project**

**Project Overview**
This project focuses on analyzing COVID-19 data across various countries and regions. The analysis includes identifying trends, detecting outliers, and visualizing key insights using data science techniques.

**Dataset Information**
Source: Downloaded CSV file containing COVID-19 case data.

**Columns:**
country: Name of the country.
country_code: ISO country code.
year_week: Year and week of data collection.
region_name: Subdivision within the country.
new_cases: Number of new COVID-19 cases reported.
tests_done: Number of tests conducted.
population: Total population of the region.
testing_rate: Testing rate per population.
positivity_rate: Percentage of positive test results.
testing_data_source: Source of the testing data.

**Objectives**
Identify trends in COVID-19 cases and testing rates over time.
Remove outliers from the dataset to improve data quality.
Visualize testing and positivity rates across different regions.
Compare the distribution of COVID cases across countries.
Data Cleaning & Processing
Missing values were identified and handled appropriately.
Outliers in new_cases were removed using the IQR method.
Categorical data was excluded from correlation analysis.

**Key Visualizations**
Scatterplots: Show relationships between testing rates, positivity rates, and new cases.
Boxplots: Display the distribution of COVID-19 cases by country, both with and without outliers.
Line Charts: Highlight trends in testing rates over time across different regions.
Bar Charts: Identify the top 10 regions with the highest number of COVID-19 cases.

**Insights & Findings**
Regions with high testing rates tend to have lower positivity rates, suggesting a well-managed testing strategy.
Significant fluctuations in case numbers were observed over different time periods, indicating COVID waves.
Outliers in new cases were removed to provide a more accurate representation of the data.
Countries with larger populations had a wider spread in COVID cases, but the positivity rate varied significantly.
