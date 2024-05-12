#  USA Ultramarathon Trends: Insights & Performance

**Objective:**

**Data Cleaning:**

**i)** For USA race events with distances of 50 km or 50 mi in the year 2020.
**ii)** Obtaining athlete age.
**iii)** Dropping irrelevant columns.
**iv)** Checking for NA values, duplicates, fixing data types, renaming columns, and reordering columns.


**Exploratory Data Analysis (EDA):**

**i)** Plotting histograms, distribution plots, violin plots, and lmplots.

**ii)** Calculating the mean difference in speed between male and female athletes, identifying the age group with the best and worst performances in the 50 mi race.

**Steps Taken:**

**STEP 1:-** Import libraries and load dataset.
**STEP 2:-** Create df2 to filter USA races for 50 km and 50 mi distances in 2020.
**STEP 3:-** Retrieve athlete age from the athlete year of birth and remove 'h' from athlete performance.
**STEP 4:-** Drop columns: athlete club, athlete country, athlete year of birth, athlete age category.
**STEP 5:-** Check for duplicates, drop NA values, and reset index.
**STEP 6:-** Check and fix data types, rename columns, and reorder them.
**STEP 7:-** Plot histogram for race length.
**STEP 8:-** Plot distribution plot for athlete average speed.
**STEP 9:-** Plot violin plot for race length and athlete average speed.
**STEP 10:-** Group data by race length and athlete gender, then calculate the mean of athlete average speeds.
**STEP 11:-** Determine the average speed for each age group in the 50-mile race, identifying both the best and worst performances.


**Conclusion:**

Through comprehensive data cleaning and exploratory analysis, insights were gained into the USA race events with distances of 50 km or 50 mi in 2020. Key findings include the mean difference in speed between male and female athletes and the identification of age groups with the best and worst performances in the 50 mi race. These insights lay the foundation for further analysis and decision-making in race event planning and athlete performance evaluation.
