# LA Crime Data Analysis (2020-2024)

This project focuses on a comprehensive analysis of crime data in Los Angeles from January 1, 2020, to September 2, 2024. The goal is to investigate the rise in crime rates during and after the COVID-19 pandemic, and understand trends in crime occurrences, victim demographics, and temporal patterns of crimes.

---

## Project Overview

The LA Crime Data Analysis project explores the following key research questions:

- **Yearly Crime Trends**: Which year recorded the highest number of crimes?
- **Geographic Distribution**: Which areas experienced the most significant crime rates?
- **Temporal Patterns**: Are crimes more prevalent at night? Which types of crimes are most common during specific times of day?
- **Victim Demographics**: Which gender or ethnic group is more likely to become a victim of crime?

---

## Dataset

The dataset used in this project was sourced from the official LA city government crime reports, covering incidents reported between January 2020 and September 2024. It contains details such as crime type, victim demographics, location, and time of day.

### **Dataset Features:**
- **incident_id**: Unique identifier for each crime report
- **date**: Date the crime occurred
- **time**: Time the crime was reported
- **year**: Year of the crime
- **location**: Geographic area of the crime
- **crime_type**: Type of crime (e.g., burglary, theft, assault)
- **victim_gender**: Gender of the victim (if available)
- **victim_age**: Age of the victim (if available)
- **victim_ethnicity**: Ethnic group of the victim (if available)
- **time_of_day**: Time of crime occurrence (categorized as day or night)
- **crime_severity**: Indicator of crime severity
- **arrest_made**: Whether an arrest was made (Yes/No)
- **outcome**: Final status of the crime report (e.g., solved, unsolved, pending)

---

## Data Preparation

1. **Data Cleaning**: The raw dataset underwent extensive cleaning to remove duplicates, null values, and errors. Entries were standardized for consistency.
2. **Data Transformation**: Categorical columns were converted into more analysis-friendly formats, and new columns were derived to analyze temporal patterns (e.g., crime by time of day).
3. **Geographic Encoding**: Geographic locations were grouped into neighborhoods to enable a clearer analysis of crime distribution across LA.

---

## Key Findings

1. **Yearly Crime Trends**: The crime rates surged in the years following the COVID-19 pandemic, with a notable increase in 2021. However, by 2023, there was a slight decline in reported incidents.
2. **Geographic Distribution**: Downtown LA, South LA, and East LA reported the highest crime rates, especially for violent crimes such as assault and robbery.
3. **Temporal Patterns**: Crimes were significantly more likely to occur at night, with theft and vandalism being particularly common during late hours.
4. **Victim Demographics**: Males were more likely to be victims of violent crimes, while females were more often associated with non-violent crimes such as theft. Ethnic minorities experienced a disproportionate rate of victimization, particularly in low-income neighborhoods.

---


## Getting Started

### Prerequisites

This project requires Python 3.x and the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- geopandas (for geographic analysis)
- folium (for map visualizations)

---

## Visualization Highlights

- **Yearly Crime Trends**: A line plot showcasing the rise and fall of crime rates from 2020 to 2024.
- **Crime Heatmaps**: Geographic heatmaps illustrating areas with the highest crime concentrations in LA.
- **Night vs. Day Crime Analysis**: A bar chart showing the percentage of crimes occurring during night vs. day, categorized by crime type.
- **Demographic Insights**: Pie charts and bar graphs displaying victim demographics such as gender, age, and ethnicity.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- **Data Source**: [https://catalog.data.gov/dataset/crime-data-from-2020-to-present](link)
- **Blog**: [https://medium.com/@malikshary09/la-crime-analysis-2020-2024-e5ca15858cba](link)
- **Dataset:**: [https://www.kaggle.com/datasets/mlkshz/la-crime-dataset-clean/data](link)
---

Feel free to reach out for any questions or feedback!
