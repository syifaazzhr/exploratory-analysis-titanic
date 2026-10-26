# Titanic Survival Analysis 

This project was developed as part of the mini bootcamp by dibimbing.id.

## Project Overview

The Titanic was a British passenger ship that sank in April 1912 after hitting an iceberg. The disaster caused the loss of more than 1,500 lives. This project uses Exploratory Data Analysis (EDA) to understand passenger survival patterns based on age and gender. The analysis includes data cleaning, statistical summaries, and data visualizations using Python. The goal is to find useful insights and understand how age and gender were related to passenger survival.

## Objectives

- Analyze passenger survival based on age and gender.
- Identify survival patterns across different passenger groups.
- Present key findings through data visualization.

## Dataset Information

The dataset contains 500 passenger records with four columns:

- `survived`: Passenger survival status (0 = Not Survived, 1 = Survived)
- `name`: Passenger name
- `sex`: Passenger gender
- `age`: Passenger age

During data cleaning, one duplicate row was removed, leaving 499 passengers. The dataset also contained 49 missing age values. These records were kept for overall survival and gender analyses but excluded from age-related analyses.

As a result, age-related analyses used 450 passengers with recorded ages.

## Tools & Libraries

- **Python** – Data analysis
- **Pandas** – Data cleaning and manipulation
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Jupyter Notebook** – Analysis and documentation

## Analysis Workflow

1. **Data Observation:** Explore the dataset structure and identify missing values and duplicates.
2. **Data Cleaning:** Remove duplicate records and prepare data for age-related analyses.
3. **Statistical Summary:** Explore passenger survival, gender, and age distributions.
4. **Exploratory Data Analysis:** Visualize survival patterns based on age and gender.
5. **Conclusion:** Summarize key findings and analysis limitations.

## Key Findings

- **Overall Survival:** Of the 499 passengers, 269 (53.9%) survived, while 230 (46.1%) did not survive.
- **Gender:** Female passengers had a much higher survival rate (about 93%) than male passengers (about 25%).
- **Age Groups:** Children had the highest survival rate (94.4%), while elderly passengers had the lowest (29.2%) among passengers with recorded ages.
- **Age and Gender:** Female passengers generally had higher survival rates across most age groups, although children showed a different pattern.

## Conclusion

The analysis shows that age and gender were related to passenger survival. Female passengers had higher survival rates than males, while children had the highest survival rate among the age groups.

These findings describe patterns in the dataset and do not prove the causes of survival differences.
