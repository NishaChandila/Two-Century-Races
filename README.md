# Ultramarathon Trends: Insights & Performance

## Introduction

This project provides an in-depth analysis of ultramarathon race data from the USA, focusing on races held in 2020 with distances of 50 km or 50 miles. The goal is to uncover key performance insights, including differences in race performance by age and gender. By analyzing this data, we aim to understand athlete performance trends and offer actionable recommendations for future race events and athlete preparation.

- ULtramarathon [Python EDA](https://github.com/NishaChandila/Two-Century-Races/blob/main/Race_Analysis.ipynb)

## Data Structure

The dataset includes the following columns:

- **Race Name**: Name of the ultramarathon event.
- **Date**: Date of the race.
- **Distance**: Distance of the race (50 km or 50 mi).
- **Athlete Name**: Name of the participant.
- **Age**: Athlete’s age at the time of the race.
- **Gender**: Gender of the athlete (Male/Female).
- **Time**: Time taken by the athlete to complete the race (in hours, minutes).
- **Speed**: Average speed of the athlete (km/h or mi/h).
- **Country**: The country the athlete represents (USA only).
- **Club**: Club or organization the athlete is associated with (if available).

## Executive Summary

In this analysis, we focused on filtering the dataset to include only ultramarathon races from 2020 in the USA with distances of 50 km and 50 miles. The following steps were performed:

1. **Data Cleaning**: 
    - Filtered for relevant races (50 km and 50 mi in the USA for 2020).
    - Calculated athlete ages and cleaned the performance data.
    - Removed duplicates, handled missing values, and fixed data types for clarity.

2. **Exploratory Data Analysis (EDA)**:
    - **Race Length Distribution**: We visualized the distribution of races by length to understand the types of events covered.
    - **Athlete Speed Distribution**: Distribution plots were created to analyze the speed of athletes.
    - **Gender and Age Group Comparisons**: Using violin plots, we compared average speed distributions between male and female athletes and across different age groups.
    - **Performance Insights**: The performance of male vs. female athletes was examined, and the best and worst-performing age groups were identified.

3. **Key Insights**:
    - There were noticeable differences in average speeds between male and female athletes, with males generally achieving faster times.
    - Age groups performed differently in the 50 mi race, with younger athletes performing better overall.
    - Distances of 50 mi saw a significant variation in performance based on gender, age, and experience level.

- ULtramarathon [Python EDA](https://github.com/NishaChandila/Two-Century-Races/blob/main/Race_Analysis.ipynb)

## Recommendations

Based on the analysis, the following recommendations can be made:

1. **Encourage Age-Specific Training Plans**: 
   - Young athletes (20-30 years old) performed significantly better in the 50 mi races. Targeted training programs for older athletes (40+ years) could help enhance their performance in future races.

2. **Enhance Gender-Specific Support**:
   - The performance gap between male and female athletes suggests that creating gender-specific race strategies, nutrition plans, and recovery support could help improve female athlete performance in ultramarathons.

3. **Event Strategy for 50 mi Races**:
   - The 50 mi race data shows a higher variance in performance compared to shorter events. Race organizers may consider offering different pacing categories for better competitive balance, encouraging athletes to participate without feeling overwhelmed by the distance.

4. **Focus on Regional Events for Local Athletes**:
   - Based on performance data by region, focusing on more localized ultramarathon events may encourage athletes to participate in races suited to their level and training.

5. **Use Insights for Athlete Development**:
   - Data can be used by coaches and sports organizations to create age-specific training programs that optimize speed and endurance, especially for those participating in the 50 mi category.

By utilizing these insights, race organizers, coaches, and athletes can better prepare for future ultramarathons, improve performance outcomes, and enhance the overall experience of participants.

- ULtramarathon [Python EDA](https://github.com/NishaChandila/Two-Century-Races/blob/main/Race_Analysis.ipynb)
