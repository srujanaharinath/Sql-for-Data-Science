# 📊 COVID-19 Data Analysis Project

# 📖 Project Overview
This project analyzes COVID-19 case trends, testing rates, and regional impacts using Python and data visualization techniques. It aims to identify patterns and insights from the dataset.

# 📂 Dataset Information
File Name: `data.csv`
Columns:
  - `country`: Country name
  - `region_name`: Region within the country
  - `year_week`: Time period (Year-Week format)
  - `new_cases`: Number of newly reported COVID-19 cases
  - `testing_rate`: Number of tests conducted per population
  - `positivity_rate`: Percentage of positive cases from total tests

# 📊 Visualizations
**1. Box Plot (After Removing Outliers)**
- Shows distribution of COVID cases across countries.
- Helps identify data spread and remove extreme outliers.

**2. Line Plot (Trends Over Time)**
- Displays COVID cases over weeks/months.
- Helps in tracking the pandemic’s progression.

**3. Correlation Heatmap**
- Analyzes relationships between testing rate, positivity rate, and new cases.
- Helps understand how testing affects reported cases.

**4. Bar Chart (Top Affected Regions)**
- Highlights regions with the highest COVID cases.

# 🧐 Key Findings
- High testing rates generally result in lower positivity rates.
- Certain regions had extreme spikes in cases (identified and handled through outlier removal).
- Trend analysis shows waves of COVID outbreaks at different time periods.
