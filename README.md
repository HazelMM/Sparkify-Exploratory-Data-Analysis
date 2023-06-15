# Sparkify Churn Analysis

This project focuses on analyzing churn in Sparkify, a fictitious music streaming service. The dataset provides valuable insights into user behavior and can help identify factors that contribute to churn.

## Overview

- The dataset has a shape of (286500, 18) and consists of 226 unique users.
- After data cleaning and preprocessing, the dataset contains 278154 rows and 21 columns.
- The following libraries were imported for data analysis:
  - pandas
  - numpy
  - datetime
  - seaborn
  - matplotlib.pyplot

## Exploratory Data Analysis

The exploratory data analysis covered the following aspects:

1. Gender and Level:
   - Analyzed the distribution of genders and user levels (paid or free) among the dataset.
   - Explored the relationship between gender/level and churn rates.

2. Location:
   - Investigated user locations and identified any patterns related to churn.
   - Examined the geographical distribution of users and its impact on churn.

3. Page Analysis:
   - Utilized page-level data to evaluate user engagement and behavior.
   - Explored the number of sessions per user and its relationship with churn.

4. Average Number of Sessions:
   - Calculated the average number of sessions for users who churned and those who did not.
   - Compared the session counts to determine if frequent app usage affects churn rates.

## Conclusions

- Based on the sample data, the frequency of app usage appears to be a significant indicator of churn. Frequent users tend to have lower churn rates compared to less active users.
- The average session count for users who did not churn was 15.25, while users who churned had an average session count of 10.33. This suggests that users who engage with the app more frequently are less likely to churn.
- The data indicates that there is a higher proportion of active users compared to users who churned. This implies that the app has a relatively stable user base, but there is room for improvement in reducing churn rates.
- The data also reveals that there are more paid users than free users within the sample. This suggests that the app may have a successful monetization strategy, as paid users are more prevalent.
- Additionally, the data shows that most days in the sample data had only one user who churned. This could indicate that churn events are relatively sporadic and not widespread.
- For machine learning purposes, it would be necessary to normalize the data by applying preprocessing techniques such as scaling or standardization. This normalization step ensures that the data is on a consistent scale and can be effectively used in machine learning algorithms.

## Future Steps

- Implement strategies to encourage frequent app usage and improve user engagement.
- Explore features that may have a stronger correlation with churn to develop more accurate churn prediction models.
- Continuously monitor churn rates and assess the effectiveness of retention strategies.

Feel free to explore the code and the analysis in detail. Contributions and feedback are welcome!

