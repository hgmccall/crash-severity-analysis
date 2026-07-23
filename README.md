# crash-severity-analysis
Exploratory data analysis project examining 338K+ North Carolina crash records to uncover relationships between weather, location, traffic conditions, and crash severity.
# North Carolina Accident Severity Analysis

An exploratory data analysis project examining how weather conditions, time of day, traffic signals, and location type influence accident severity across North Carolina.

---

## Overview

This project analyzes traffic accident data from the US Accidents (2016–2023) dataset to identify patterns and factors associated with accident severity in North Carolina.

The analysis focuses on understanding how environmental and roadway conditions—including weather, daylight conditions, traffic signals, and city type—relate to accident frequency and severity. The project demonstrates data cleaning, feature engineering, data visualization, and exploratory data analysis techniques using Python.

---

## Objectives

The primary goals of this project were to:

- Analyze accident severity trends across North Carolina
- Examine the impact of weather conditions on traffic accidents
- Compare accident severity during daytime and nighttime hours
- Investigate whether traffic signals influence accident severity
- Explore differences in accident severity across urban, suburban, and rural areas
- Practice data cleaning, feature engineering, and visualization techniques

---

## Dataset

Source: US Accidents (2016–2023) Dataset

Original Dataset Size:
- 7.7 million+ accident records
- Multiple states across the United States
- Dozens of environmental, geographic, and traffic-related variables

Filtered Dataset:
- North Carolina accidents only
- 338,199 accident records
- 12 selected variables after cleaning

---

## Data Cleaning & Preparation

Several preprocessing steps were performed to improve data quality and analytical clarity:

### Column Reduction

Removed nonessential columns including:

- Geographic coordinates
- Timezone information
- Airport codes
- Descriptive text fields
- Twilight-related variables
- Road feature indicators

This reduced dataset complexity and focused the analysis on relevant variables.

### Missing Data Handling

Missing precipitation values were replaced with 0 to represent the absence of recorded precipitation.

### Weather Feature Engineering

Individual weather conditions were consolidated into broader categories:

- Clear
- Cloudy
- Rain
- Snow/Ice
- Fog/Haze
- Other

Grouping weather conditions improved readability and simplified visual analysis.

### City Classification

Cities were classified into three location categories:

- Urban
- Suburban
- Rural

This allowed accident severity comparisons across different population densities and transportation environments.

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- Matplotlib
- Seaborn

### Development Tools

- Jupyter Notebook

---

## Analysis & Visualizations

### Severity vs. Time of Day

A count plot was created to compare accident severity during:

- Daytime
- Nighttime

This visualization helped identify differences in accident frequency and severity based on lighting conditions.

### Severity by City Type

A heatmap was used to visualize accident severity across:

- Urban areas
- Suburban areas
- Rural areas

This allowed comparison of severity patterns based on location type.

### Weather Conditions and Severity

A count plot examined accident frequency and severity across grouped weather categories:

- Clear
- Cloudy
- Rain
- Snow/Ice
- Fog/Haze

### Traffic Signals and Severity

A stacked bar chart was used to analyze whether the presence of a traffic signal correlated with accident severity levels.

---

## Key Findings

### Location Matters

Rural areas experienced fewer total accidents than urban areas but showed a higher proportion of severe accidents.

### Weather Impacts Accident Frequency

Cloudy and rainy conditions were associated with a substantial number of accidents, indicating that reduced visibility and road conditions may contribute to increased risk.

### Traffic Signals Influence Accident Patterns

Accident distributions differed between intersections with and without traffic signals, suggesting roadway infrastructure plays a role in traffic safety outcomes.

### Day vs. Night Trends

Most accidents occurred during daytime hours, though further analysis could be conducted to compare severity rates between daytime and nighttime incidents.

---

## Challenges & Solutions

### Challenge: Large Dataset Size

The original dataset contained more than 7 million records and dozens of variables, making analysis and visualization difficult.

### Solution

The dataset was filtered to North Carolina records and unnecessary columns were removed to improve performance and simplify analysis.

---

### Challenge: Numerous Weather Categories

The dataset contained many similar weather descriptions that made visualizations difficult to interpret.

### Solution

Weather conditions were grouped into broader categories such as Clear, Cloudy, Rain, and Snow/Ice to improve readability and analytical consistency.

---

## Key Learnings

Through this project I gained experience with:

- Data cleaning and preprocessing
- Exploratory data analysis
- Feature engineering
- Data visualization
- Large dataset manipulation
- Pandas DataFrame operations
- Statistical interpretation of visualizations
- Communicating analytical findings

---

## Future Improvements

Potential enhancements include:

- Predictive modeling of accident severity using machine learning
- Geographic visualization using mapping tools
- Time-series analysis of accident trends
- Additional feature engineering using roadway and environmental variables
- Development of an interactive dashboard for accident exploration

---

## Author

Hailey McCall

LinkedIn:  www.linkedin.com/in/hailey-mccall

GitHub: https://github.com/haileymccall

