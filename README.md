## Ultramarathon Trends: Insights & Performance

This repository contains a comprehensive analysis of ultramarathon race data from the USA, focusing on races with distances of 50 km or 50 mi in the year 2020. The project involved cleaning and analyzing the data to uncover trends and performance insights, particularly in relation to athlete performance by age and gender.

**Project Overview**

**Objective**

The primary objective of this project was to analyze ultramarathon race events in the USA with distances of 50 km and 50 mi during 2020. The goal was to gain insights into athlete performance, particularly the differences in speed between male and female athletes and the performance of different age groups in the 50 mi race.

**Problem Statement**

The dataset contained raw data that required extensive cleaning to ensure accuracy and reliability in the analysis. The main challenges included filtering relevant race events, calculating athlete ages, handling missing values, and preparing the data for exploratory analysis. Additionally, it was essential to visualize the data to uncover meaningful trends and performance metrics.

**Solution**

To address these challenges, the following steps were taken:

**1. Data Cleaning:**

1. Filtered the dataset to focus on USA race events with distances of 50 km or 50 mi in 2020.

2. Retrieved athlete ages from their year of birth.
 
3. Removed irrelevant columns, such as athlete club, country, year of birth, and age category.

4. Checked for and removed duplicate entries and NA values, then reset the index.

5. Fixed data types, renamed columns for clarity, and reordered columns for better readability.

**Exploratory Data Analysis (EDA):**

1. Plotted histograms to visualize the distribution of race lengths.

2. Created distribution plots to analyze athlete average speeds.

3. Used violin plots to compare race length and athlete average speed distributions.

4. Calculated the mean difference in speed between male and female athletes.

5. Identified the age groups with the best and worst performances in the 50 mi race by calculating the average speeds.

**Tools Used**

**Python:** For data cleaning, manipulation, and analysis.

**Pandas:** To filter data, handle missing values, and perform grouping and aggregation.

**Matplotlib/Seaborn:** For creating visualizations like histograms, distribution plots, and violin plots.

**Jupyter Notebook:** To document the data cleaning process, perform exploratory analysis, and visualize findings.

**Key Steps in the Analysis**

**1. Import Libraries and Load Dataset:** The necessary Python libraries were imported, and the dataset was loaded for processing.

**2. Data Filtering:** A filtered DataFrame (df2) was created to focus on USA races with 50 km and 50 mi distances in 2020.

**3. Age Calculation and Data Cleaning:** Athlete ages were calculated from their year of birth, and unnecessary characters (like 'h' in performance data) were removed. Irrelevant columns were dropped.

**4. Data Quality Checks:** The dataset was checked for duplicates, missing values were handled, and the data types were corrected. Columns were renamed and reordered for clarity.

**5. Visualization and Analysis:** Various plots were created to visualize race length distributions, athlete average speeds, and performance comparisons across different demographics.

**6. Performance Insights:** The mean difference in speeds between male and female athletes was calculated, and the best and worst performing age groups in the 50 mi race were identified.

**Conclusion**

Through detailed data cleaning and exploratory analysis, the project provided valuable insights into ultramarathon race events in the USA for 2020. The analysis revealed key trends, such as the difference in speeds between male and female athletes and the performance of various age groups in long-distance races. These insights can be instrumental in guiding future race event planning and evaluating athlete performance.
