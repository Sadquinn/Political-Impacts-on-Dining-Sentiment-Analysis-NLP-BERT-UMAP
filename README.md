# Impact of Political Shifts on Dining Sentiment  
### Analyzing the Effect of the 2016 U.S. Presidential Election on Yelp Restaurant Reviews

## Project Overview
This project investigates whether the 2016 U.S. presidential election influenced the sentiment and ratings of Yelp restaurant reviews in states that voted for the losing candidate. Using deep learning–based sentiment analysis, we examine whether political disappointment correlated with changes in consumer sentiment expressed through online restaurant reviews.

The analysis focuses on:
- The two states with the highest support rate for each major political party
- One politically neutral swing state as a control group
- A comparison of sentiment and ratings **two months before and after** the election

The goal is to understand how major political events may indirectly affect consumer behavior and online review culture.

---

## Executive Summary
Major political events can have broad emotional and psychological impacts on the public, potentially influencing everyday behaviors such as dining preferences and online reviews. This project applies natural language processing and deep learning techniques to Yelp review data to measure sentiment shifts surrounding the 2016 U.S. election.

By comparing sentiment trends across politically polarized states and a neutral control state, this study evaluates whether election outcomes had a measurable effect on restaurant review sentiment and overall ratings. The findings aim to provide insights into the intersection of politics, consumer behavior, and digital platforms.

---

## Project Background
The 2016 U.S. presidential election was one of the most politically divisive events in recent history. Emotional responses to election outcomes may manifest beyond traditional political discourse and influence unrelated domains, including consumer experiences and online behavior.

This project explores whether political sentiment spilled over into Yelp restaurant reviews, particularly in states that strongly supported the losing candidate. By leveraging structured Yelp datasets and deep learning–based sentiment analysis, the study identifies potential shifts in sentiment over time while controlling for geographic and political variation.

---

## Key Stakeholders
- **Restaurants and Business Owners**  
  Gain insights into how external political events may affect customer sentiment and ratings.
  
- **Yelp Platform**  
  Enhance understanding of user engagement patterns and sentiment dynamics following major societal events.
  
- **Marketing and Strategy Teams**  
  Use sentiment insights to align marketing strategies with customer preferences and emotional trends.

Understanding these dynamics allows businesses to better connect marketing efforts with customer sentiment, ultimately improving satisfaction and profitability.

---

## Data Sources
This project utilizes the Yelp Open Dataset, including:

- **yelp_business**  
  Business attributes, ratings, categories, and geospatial data (latitude, longitude)

- **yelp_user**  
  User engagement metrics such as review counts and useful votes

- **yelp_review**  
  Review text, star ratings, and timestamps for sentiment analysis

- **yelp_checkin**  
  Customer foot traffic patterns over time

- **yelp_tip**  
  Short user comments and trending features

Together, these datasets provide comprehensive coverage of business performance, customer behavior, and location-based trends.

---

## Methodology

### 1. Data Cleaning and Integration
- Merge datasets using shared identifiers (`business_id`, `user_id`)
- Filter reviews by state and election time window
- Preprocess text data (tokenization, stopword removal, normalization)

### 2. Sentiment Analysis
- Apply deep learning–based NLP models to Yelp reviews and tips
- Extract sentiment scores and polarity trends
- Compare sentiment distributions before and after the election

### 3. Geospatial and Behavioral Analysis
- Map restaurant locations using latitude and longitude
- Analyze regional differences in sentiment and ratings
- Examine check-in trends to understand behavioral changes

### 4. Machine Learning Applications
- Clustering (e.g., K-means) to group similar businesses or users
- Collaborative filtering to identify customer preference patterns
- Trend analysis across political and geographic segments

---

## Evaluation Metrics
Project outcomes are evaluated using:
- Changes in sentiment scores
- Differences in average star ratings
- Review volume and engagement metrics
- Check-in trends as a proxy for foot traffic

These metrics help assess whether political events coincided with measurable shifts in consumer behavior.

---

## Key Insights and Contributions
- Provides evidence on how political events may influence non-political consumer sentiment
- Demonstrates the application of deep learning NLP in real-world social data
- Combines structured, unstructured, and geospatial data for holistic analysis
- Offers actionable insights for businesses and digital platforms

---

## Future Work
Planned extensions include:
- Longer post-election analysis windows
- Incorporation of news and social media sentiment
- More granular demographic segmentation
- Advanced architectures such as transformers for sentiment modeling

This project highlights the importance of contextual awareness when interpreting online consumer data, particularly during periods of major societal change.
