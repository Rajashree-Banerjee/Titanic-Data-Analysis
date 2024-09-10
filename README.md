
# Titanic Data Analysis Project

This project is an **end-to-end data analysis** of the famous Titanic dataset, conducted using **SQL, Python, Power BI**, and **Tableau**. The analysis focuses on survival rates, passenger ages, and how these statistics vary across different passenger classes, with a particular focus on comparing **Class 1**, **Class 2** and **Class 3** passengers.

## Overview

The goal of this project is to extract insights from the Titanic dataset, particularly regarding:
- The number of passengers who survived.
- Age distribution among survivors.
- Differences in survival rates and age distributions across passenger classes (Class 1 vs Class 3).

## Tools Used

- **SQL**: To query and analyze the dataset directly from a relational database.
- **Python**: For data cleaning, preprocessing, and analysis (using `pandas`, `Ipython-sql`, etc.).
- **Power BI**: For creating visual reports and dashboards to represent the data visually.
- **Tableau**: For advanced visualizations and interactive exploration of the data.

## Project Workflow

1. **Data Exploration and Cleaning**:
   - The Titanic dataset was explored using Python and SQL to identify missing values, outliers, and data inconsistencies.
   - Data cleaning included handling missing values in the `Age` and `Fare` columns.

2. **Data Analysis**:
   - SQL queries were used to analyze survival rates, age distributions, and the relationship between survival and passenger class.
   - In Python, detailed analysis and visualizations were created using `Ipython-sql` and ``.

3. **Visualizations in Power BI and Tableau**:
   - **Power BI**: Visualized survival rates, age distributions, and compared these statistics across different passenger classes.
   - **Tableau**: Created detailed graphs showing how survival rates and age varied for passengers in **Class 1** and **Class 3**, highlighting significant differences between the two groups.

## Key Insights

- **Survival Rates**: The survival rate was significantly higher for **Class 1** passengers compared to **Class 3** passengers.
- **Age Distribution**: Younger passengers had a higher survival rate, particularly in Class 1.
- **Class Differences**: Graphical analysis showed stark differences in survival patterns between Class 1 and Class 3 passengers, with Class 1 having better access to lifeboats.

## Installation and Setup

To run the analysis and replicate the results, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/titanic-data-analysis.git
   cd titanic-data-analysis
