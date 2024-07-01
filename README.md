
# Salary Prediction of Data Professions

## Overview

This project aims to predict salaries for data-related professions based on various factors. The dataset used contains information about professionals' designations, age, gender, and salary. By analyzing this data, we gain insights into salary distributions, gender-based differences, and other relevant trends.

## Data

- The dataset (`Salary Prediction of Data Professions.csv`) includes the following columns:
    - `DESIGNATION`: Job title or role
    - `AGE`: Age of the professional
    - `SEX`: Gender (encoded as 0 for female and 1 for male)
    - `SALARY`: Salary in the corresponding profession

## Methodology

1. **Data Loading and Cleaning**:
    - Loaded the dataset using Pandas.
    - Replaced infinite values with NaN.
    - Explored missing values in categorical variables.

2. **Exploratory Data Analysis (EDA)**:
    - Investigated the distribution of gender and age.
    - Created visualizations:
        - Bar chart showing the distribution of gender.
        - Histogram of age distribution.
        - Bar chart of average salary by gender.
        - Box plot of salary distribution by gender.
        - Histogram with KDE for salary distribution.
        - Box plot of salary.

3. **Average Salary by Categorical Features**:
    - Explored average salary variations based on categorical features (`DESIGNATION` and `UNIT`).
    - Plotted bar charts to visualize these variations.

## Results

- We observed differences in salary based on gender.
- The EDA provided insights into salary distributions and potential outliers.
- Further analysis can explore additional factors affecting salaries.


## Conclusion

In this project, we explored salary prediction for data-related professions using a dataset that includes information about designations, age, gender, and salaries. Here are the key takeaways:

1. **Gender Disparities**: We observed differences in salaries based on gender. Further investigation into the underlying factors contributing to these disparities could be valuable.

2. **EDA Insights**: Our exploratory data analysis (EDA) provided insights into salary distributions, potential outliers, and trends. Visualizations such as histograms, box plots, and bar charts helped us understand the data better.

3. **Next Steps**: Moving forward, consider the following steps:
   - Feature engineering: Create new features that might enhance model performance.
   - Advanced modeling: Explore machine learning algorithms beyond what we've used so far.
   - Additional factors: Investigate other variables (education, experience, location) that may impact salaries.


## Future Work

- Consider feature engineering (e.g., creating new features) to improve model performance.
- Explore more advanced machine learning models for salary prediction.
- Investigate other factors (education, experience, location) that may impact salaries.

