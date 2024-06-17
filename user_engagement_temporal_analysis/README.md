# User Engagement Temporal Analysis

## Project Description

This project aims to analyze user engagement and conversion rates across different times of the day on an e-commerce platform using the `ga4_obfuscated_sample_ecommerce` dataset. 
By understanding how user behavior varies throughout the day, the platform can optimize ad campaigns and content delivery schedules to maximize engagement and revenue.

## Key Features

- **Data Segmentation**: 
  - Segment data into different times of the day (dawn, morning, afternoon, night) for granular analysis of user engagement patterns.

- **Engagement Metrics**: 
  - Analyze various metrics including unique users, total events, session starts, purchases, total purchase value, add-to-cart actions, and engagement time.

- **Statistical Analysis**: 
  - Employ statistical tests such as Shapiro-Wilk, Levene's test, ANOVA, and Kruskal-Wallis to determine significant differences in user engagement and conversion rates across different time segments.

- **Data Visualization**: 
  - Use techniques like boxplots, line plots, and heatmaps to communicate findings and provide insights into user behavior patterns.

- **Correlation Analysis**: 
  - Explore correlations between different engagement metrics to identify potential relationships and dependencies.

- **Hypothesis Testing**: 
  - Test the hypothesis that the time of day influences customer engagement behavior by conducting statistical tests on various engagement variables.

- **Non-Parametric Tests**: 
  - When data does not meet the normality assumptions for ANOVA, employ non-parametric tests like the Kruskal-Wallis test to ensure robust analysis.

## Technologies Used

- **Programming Languages**: 
  - Python

- **Data Storage and Querying**: 
  - Google BigQuery

- **Data Manipulation and Analysis**: 
  - Pandas, SciPy

- **Data Visualization**: 
  - Seaborn, Matplotlib

## Key Findings

- **Stability in User Engagement**: 
  - The analysis did not find statistically significant differences in user engagement and conversion rates across different times of the day for the analyzed variables.
  - The platform's user engagement appears stable throughout the day, suggesting that time alone may not significantly influence user behavior.
