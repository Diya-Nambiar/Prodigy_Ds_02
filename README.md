# Prodigy_Ds_02
# Titanic Survival Analysis – Prodigy InfoTech Data Science Task 2

This project was completed as part of my Data Science Internship with **Prodigy InfoTech**. The goal of the task was to explore, clean, and analyze a real-world dataset to draw insights from it. I chose the widely studied Titanic dataset to identify key factors that influenced passenger survival during the disaster.

## Objective

To perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset, in order to identify patterns and relationships that affected survival outcomes.

## Dataset Information

- **Source**: provided by **Prodigy InfoTech** as part of the Data Science Internship program
- **Features Included**:
  - Passenger demographics (Age, Sex)
  - Socioeconomic variables (Pclass, Fare)
  - Travel-related details (Embarked, Ticket, Cabin)
  - Survival outcome (Survived)

## Tools and Technologies Used

- **Programming Language**: Python
- **Environment**: Jupyter Notebook
- **Libraries**:
  - `pandas` and `numpy` for data manipulation
  - `matplotlib` and `seaborn` for data visualization
  - `missingno` for handling and visualizing missing values

## Workflow Overview

### 1. Data Exploration
- Loaded the dataset and examined its structure
- Inspected the number and types of variables
- Identified missing values and data inconsistencies

### 2. Data Cleaning
- Imputed missing values in the **Age** column using median values grouped by class and gender
- Dropped the **Cabin** column due to excessive missing data
- Filled missing **Embarked** values with the mode
- Removed irrelevant or redundant columns: **PassengerId**, **Ticket**, and **Name**

### 3. Exploratory Data Analysis (EDA)
- Analyzed survival rates across different variables:
  - Gender
  - Passenger class (Pclass)
  - Age groups
  - Fare distribution
  - Embarked locations
- Created a correlation heatmap to understand relationships between numerical features
- Applied visualizations to identify trends and outliers

## Key Insights

- Female passengers had a significantly higher survival rate than males.
- Passengers in first class were more likely to survive than those in second or third class.
- Younger passengers (especially children) had higher chances of survival.
- Higher fare amounts appeared to correlate with survival.
- The port of embarkation showed some influence on survival outcomes.

## Conclusion
This project provided valuable experience in:

- Working with imperfect real-world data
- Developing a structured approach to data cleaning
- Using visualization to uncover insights
- Communicating findings clearly and effectively
