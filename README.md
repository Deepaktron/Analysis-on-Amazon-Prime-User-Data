# Analysis-on-Amazon-Prime-User-Data

# Project Description: Amazon Prime Users Analysis

## Project Overview

The objective of this project is to conduct an in-depth analysis of Amazon Prime users, focusing on their demographics, subscription behaviors, payment patterns, usage frequency, device preferences, engagement metrics, and content preferences. By leveraging this data, Amazon Prime can optimize its services, tailor user experiences, and develop strategies to minimize churn while maximizing user engagement.

## Data Description

The dataset comprises various features capturing different aspects of Amazon Prime users:

- **User ID**: A unique identifier for each user.
- **Name**: The user's full name.
- **Email Address**: The user's email address.
- **Username**: The user's chosen username.
- **Date of Birth**: The user's date of birth, used to calculate age.
- **Gender**: The user's gender (e.g., Male, Female, Other).
- **Location**: The user's geographical location.
- **Membership Start Date**: The date when the user initiated their membership.
- **Membership End Date**: The date when the user's membership ended, if applicable.
- **Subscription Plan**: The type of subscription plan the user has (e.g., Monthly, Annual).
- **Payment Information**: The user's preferred payment method (e.g., Credit Card, PayPal).
- **Renewal Status**: Indicates whether the membership is auto-renewed or manually renewed.
- **Usage Frequency**: How often the user engages with Amazon Prime services (e.g., daily, weekly).
- **Purchase History**: Records of purchases made by the user on Amazon Prime.
- **Favorite Genres**: User’s preferred content genres (e.g., Action, Drama, Comedy).
- **Devices Used**: Types of devices the user employs to access Amazon Prime (e.g., smartphone, tablet, smart TV).
- **Engagement Metrics**: Quantitative metrics reflecting user engagement (e.g., watch time, number of logins).
- **Feedback/Ratings**: User ratings and feedback on various services and content.
- **Customer Support Interactions**: Records of interactions the user had with customer support.
- **TLD**: The top-level domain of the user's email address (e.g., .com, .net, .org).

## Analysis Breakdown

### 1. Demographic Analysis

#### Age Calculation and Distribution
- **Calculation**: Determine the age of users by subtracting the birth year from the current year.
- **Visualization**: Plot age distribution to understand the age range of users and identify the most common age groups.

#### Gender Distribution
- **Analysis**: Count and visualize the number of users by gender to identify gender representation within the user base.
- **Segmentation**: Further segment analysis by other features like subscription plans and engagement metrics.

#### Top-Level Domains (TLD)
- **Distribution**: Analyze the frequency of different top-level domains in email addresses to understand user origins and email preferences.

### 2. Membership and Subscription Analysis

#### Subscription Plan Analysis
- **Overall**: Assess the distribution of different subscription plans among users.
- **Gender-Based**: Compare subscription plan preferences between male and female users.
- **Visualization**: Use bar charts and pie charts to represent the findings.

#### Subscription Start Day Analysis
- **Investigation**: Analyze which days users typically start their subscriptions to identify any trends or peak times for new sign-ups.
- **Visualization**: Utilize heatmaps and line graphs to illustrate subscription start day trends.

#### Membership Duration
- **Calculation**: Compute the duration of each membership by subtracting the start date from the end date.
- **Visualization**: Plot histograms or box plots to display membership duration and identify typical membership lengths.

#### Churn Analysis & Prediction
- **Factors**: Identify factors contributing to user churn such as low engagement, negative feedback, and non-renewal status.
- **Modeling**: Develop predictive models to identify users at high risk of churn.
- **Visualization**: Use scatter plots and decision trees to represent churn patterns and prediction results.

### 3. Payment Analysis

#### Payment Patterns
- **Overall Analysis**: Assess the prevalence of different payment methods among users.
- **Gender-Based Analysis**: Compare payment method preferences between male and female users.
- **Plan-Based Analysis**: Evaluate payment methods across different subscription plans.
- **Visualization**: Use pie charts and bar graphs to illustrate payment patterns.

### 4. User Activity and Engagement

#### Usage Patterns
- **Frequency Analysis**: Determine how often users engage with Amazon Prime services (e.g., daily, weekly).
- **Visualization**: Display findings using histograms and line charts.

#### Device Analysis
- **Device Usage**: Analyze the types of devices used by users to access Amazon Prime.
- **Visualization**: Use pie charts and bar graphs to represent device usage patterns.

#### Engagement Metrics
- **Overall Engagement**: Evaluate overall user engagement using metrics like watch time, login frequency, and content interactions.
- **Gender-Based Engagement**: Compare engagement metrics between male and female users.
- **Plan-Based Engagement**: Assess engagement levels across different subscription plans.
- **Visualization**: Utilize bar charts, line graphs, and scatter plots to represent engagement data.

### 5. Content Preferences

#### Genre Popularity
- **Analysis**: Determine the most popular content genres among users.
- **Visualization**: Use bar charts and word clouds to illustrate genre preferences.

## Tools and Libraries Used

- **Pandas**: For efficient data manipulation, cleaning, and analysis.
- **NumPy**: For numerical computations and array operations.
- **Matplotlib**: For creating static, interactive, and animated visualizations in Python.
- **Seaborn**: For statistical data visualization, based on Matplotlib.
- **Dateutil**: For parsing and processing dates.

## Conclusion

This comprehensive analysis of Amazon Prime users provides valuable insights into user demographics, subscription behaviors, payment preferences, activity levels, device usage, engagement metrics, and content preferences. By understanding these patterns, Amazon Prime can improve service offerings, enhance user experience, develop targeted marketing strategies, and implement effective customer retention measures. The results of this analysis will enable Amazon Prime to better serve its diverse user base, optimize resource allocation, and sustain growth in a competitive market.
