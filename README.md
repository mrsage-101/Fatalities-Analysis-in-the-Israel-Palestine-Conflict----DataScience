# Fatalities Analysis in the Israel-Palestine Conflict
## Overview
This project delves into an in-depth analysis of fatalities from the Israel-Palestine conflict, using data spanning from 2000 to 2023. By employing a rigorous data science methodology, the aim is to shed light on the patterns and characteristics of the fatalities, thereby providing insights that could inform conflict resolution strategies and humanitarian aid distribution.
## Data Science Concepts Utilized
### Imports
- **Libraries Used:** `pandas` for data manipulation, `seaborn` for statistical data visualization, alongside `matplotlib` for additional plotting capabilities.
- Data cleaning and preprocessing techniques, including handling missing values and outlier detection.

#### Data Acquisition
- **Source:** The dataset was derived from a meticulously compiled collection of recorded fatalities, indicating the comprehensive capabilities of `pandas` to manage and analyze such datasets.

## Insights Derived
### Exploratory Data Analysis (EDA)
Data preprocessing focused on handling missing values, particularly within the 'age' column, where null values were replaced with the median to address the right-skewed distribution.
it segmented the data based on attributes such as year, age, and citizenship, providing a form of natural clustering that revealed distinct patterns in the fatalities.

## Data Analysis
### Analysis on Age and Gender 
It examines the age distribution of the fatalities, noting a right skew in the data and opting to replace null values with the median to handle the skewness. The report finds that the majority of fatalities are males, which aligns with the expectation that males are more likely to be on the front lines in a conflict.

### Citizenship and Geographic Distribution 
The majority of fatalities are Palestinians, with a detailed breakdown of fatalities by districts and regions, illustrating the geographic spread of the conflict's impact.

### Types of Injuries and Ammunition Used 
The analysis provides insights into the types of injuries sustained and the ammunition used, revealing that gunfire is the leading cause of fatalities, followed by explosions and shelling. It also details the distribution of ammunition types used over the years, with missiles being prominently used, especially in 2014.

### Special Focus on 2014
The report gives special attention to the spike in fatalities in 2014, analyzing the types of ammunition used and the distribution of fatalities by ammunition in that year. This analysis ties the spike in fatalities to the 2014 Gaza War, with online research corroborating the significant use of missiles by Israel during this period.

### Comparative Analysis Between Genders 
It compares the age distributions of male and female fatalities, revealing insights into the impact of the conflict across genders.
