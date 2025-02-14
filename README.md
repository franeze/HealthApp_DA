# HealthApp_DA

### Smart Strategies for a Wellness Technology Company: Analyzing Data from a Health and Fitness Device

<div style="text-align: center;"><img src="Pictures/Wellness_LOGO.png" alt="Example Image" width="200"/></div>

#### Scenario 

"In this project, I analyzed smart device usage trends to inform strategic decisions for a wellness technology company. The focus was on understanding user interactions with smart devices, identifying key health and wellness metrics, and exploring correlations between various indicators. The goal was to leverage trends in health monitoring and personalization to guide marketing strategies and enhance product offerings. I used Python for data analysis and visualization, utilizing libraries such as pandas, Seaborn, and Matplotlib to clean, process, and generate insightful charts. The findings were compiled into a comprehensive report in Jupyter Notebook, highlighting how the company can leverage these trends to better engage customers and improve their products."

.

#### 1 - Key Objectives:


1 -	Analyze Health Metrics: Examine and compare trends in health data, such as sleep patterns, physical activity, and calorie expenditure, to understand user behavior and device interaction.
  
2 - Identify Usage Trends: Discover patterns in smart device usage, and correlations between health metrics to highlight key user trends.


3 - Enhance Product and Marketing Strategy: Develop actionable recommendations based on data-driven insights to improve product features, optimize user experience, and tailor marketing strategies to better meet user needs and preferences. 

.

#### 2 - Methodology:

This project applied data analysis techniques to clean, transform, and visualize data from a smart device usage dataset. The key steps involved:

A. Data Cleaning:

- Deduplication: Removed duplicate rows from the sleep_day dataset (no duplicates found in daily_activity or weight_info).
- Handling Missing Values: Addressed missing values, notably removing the 'Fat' column from weight_info due to a high proportion of missing entries.
- Date Conversion: Standardized date columns by converting them to datetime format for consistency.


B. Data Transformation:

- Feature Engineering: Added "Active minutes" and "Active distance" columns to daily_activity by summing related metrics. Added "NoSleepBedMin" to analyze the difference between total time in bed and minutes asleep.
- Grouping & Aggregation: Aggregated data by day of the week to analyze average steps, sedentary minutes, calories, and sleep patterns.


C. Exploratory Data Analysis (EDA):
- Descriptive Statistics: Generated summary statistics to understand central tendencies and variable distributions.
- Merging Datasets: Combined daily_activity and sleep_day datasets to explore relationships between activity and sleep. Combined daily_activity and weight_info datasets to explore relationships between activity and weight.
- Correlation Analysis: Computed correlation matrices and visualized relationships between activity and health metrics using heatmaps. Explored correlations within the merged dataset to assess the interaction between activity and sleep metrics.
- Visualization
  - Created bar and regression plots to highlight:
    - Average steps, sedentary minutes, and calories by day.
    - Sleep metrics (records, minutes asleep, time in bed) by day.
    - Weight and BMI (Body Mass Index).
    - Correlations between activity variables, calories, sleep metrics and weight variables.


D. Reporting:
- Documentation: The entire process, from data cleaning to transformation and visualization, was documented for clarity and reproducibility.
- Key Findings: Summarized insights to support strategic recommendations based on the data analysis.

.

#### 3 - Outcome:
The analysis of the smart device data uncovered significant insights into user behavior, device performance, and health metrics. Advanced data cleaning, transformation, and visualization techniques highlighted key patterns and correlations between activity levels, sleep quality, and caloric expenditure. The findings reveal opportunities for enhancing product features and personalizing wellness strategies to better meet user needs. By optimizing engagement strategies based on these insights, the project demonstrates a strong capability in data-driven decision-making and provides actionable recommendations that could significantly impact product development and marketing strategies. This project underscores the potential for leveraging data to drive improvements and foster greater user satisfaction.


#### 4 - Report
 [Look at the report in Python (Click here)](DA_wellnes_tech_company.pdf)
