
# Restaurant Success Analysis


This project leverages a dataset from Yelp to explore the connection between user activity (reviews, tips, and check-ins) and how well a restaurant performs (measured by review count and ratings). The analysis aims to identify factors contributing to a restaurant's success and provide insights for businesses in the food industry.

For a detailed report on this analysis, check out the report [here](https://github.com/Shaikh-Umar-Farooq/restaurant-success-analysis/blob/main/RESTAURANTS%20SUCCESS%20report.pdf).

## Table of Contents

- [Problem Statement](#problem-statement)
- [Research Objectives](#research-objectives)
- [Hypothesis](#hypothesis)
- [Data Overview](#data-overview)
- [Analysis and Findings](#analysis-and-findings)
- [Recommendations](#recommendations)

## Problem Statement

In the competitive world of restaurants, identifying what makes a business thrive is essential for all involved. This project explores the relationship between user engagement (reviews, tips, and check-ins) and restaurant performance (review count and ratings) to uncover insights that can help businesses succeed.

## Research Objectives

1. Quantify the correlation between user engagement (reviews, tips, check-ins) and review count/average star ratings.
2. Analyze the impact of sentiments on reviews count and average star ratings.
3. Identify time trends in user engagement.

## Hypothesis

1. Higher levels of user engagement (more reviews, tips, and check-ins) correlate with higher review count and ratings for restaurants.
2. Positive sentiment expressed in reviews and tips contributes to higher overall counts for restaurants.
3. Consistent engagement over time is positively associated with sustained business success for restaurants.

## Data Overview

- The dataset is a subset of Yelp data, containing information about businesses across 8 metropolitan areas in the USA and Canada.
- The original data is shared by Yelp as JSON files, including business, review, user, tip, and check-in data.
- The JSON files are stored in databases for easy data retrieval.

## Analysis and Findings

### Data Distribution
- Out of 150k businesses, 35k are open restaurants.
- The analysis focuses on the distribution of business success metrics (review count and average rating).

### Correlation Between User Engagement and Ratings
- Higher ratings generally correspond to higher average review, check-in, and tip counts.
- Restaurants rated 4 stars exhibit the highest engagement, with a downward trend for ratings above 4.
- Few restaurants with over 50 reviews have a 5-star rating, suggesting a more balanced range of reviews for consistently popular places.

### Correlation Between User Engagement Metrics
- Strong positive correlations exist between review count, tip count, and check-in count.
- Higher activity in one area tends to be associated with higher activity in others, indicating interlinked user engagement.

### User Engagement and Business Success
- Higher-rated businesses exhibit increased user engagement across reviews, tips, and check-ins.
- Maintaining high service and quality standards drives more reviews, check-ins, and tips, which are critical metrics of customer engagement and satisfaction.

### City and State Analysis
- Philadelphia emerges as the top city with the highest success score, combining high ratings and active user engagement.
- Other top cities include Tampa, Indianapolis, and Tucson, suggesting thriving restaurant scenes in these areas.

### Time Trends in User Engagement
- Successful businesses, particularly those with higher ratings (above 3.5), exhibit consistent or increasing user engagement over time.
- High-rated restaurants maintain steady or growing levels of user engagement, reflecting ongoing customer satisfaction.

### Sentiment Analysis
- Higher counts of "useful," "funny," and "cool" reviews suggest greater user engagement and satisfaction, contributing to a restaurant's success.

### Peak Hours
- The busiest hours for restaurants, based on user engagement, span from 4 pm to 1 am.
- Knowing peak hours allows businesses to optimize staffing levels and resource allocation during these times.

## Recommendations

- Utilize insights from the analysis of various metrics (user engagement, sentiment of reviews, peak hours, elite users) to make informed decisions and drive success.
- Collaborate with elite users and leverage their influence to amplify promotional efforts, increase brand awareness, and drive customer acquisition.
- Adjust operating hours or introduce special promotions to capitalize on increased demand during peak hours.
- Less successful businesses should focus on strategies to enhance user engagement over time, such as improving service quality and responding to customer feedback.
- Cities with high success scores present opportunities for restaurant chains to expand or invest further.

This project provides valuable insights into the factors contributing to restaurant success and offers data-driven recommendations for businesses in the food industry to improve their performance and customer engagement.
