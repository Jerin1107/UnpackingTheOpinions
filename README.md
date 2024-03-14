# Reddit Sentiment Analysis Project

## Overview
This project focuses on conducting sentiment analysis on discussions related to abortion from two Reddit communities: r/prochoice and r/prolife. The sentiment analysis aims to understand the attitudes, trends, and themes prevalent in these communities regarding abortion-related discussions.

## Methods
Several methodologies were employed in this study:

1. **Python Reddit API Wrapper (PRAW):** Used to interact with Reddit's API, facilitating data retrieval from subreddits, posts, and comments.
2. **Valence Aware Dictionary and Sentiment Reasoner (VADER):** Employed for sentiment analysis, VADER is capable of handling emoticons, slang, and informal language prevalent in social media.
3. **Latent Dirichlet Allocation (LDA):** Utilized for topic modeling to identify underlying themes in a collection of documents.
4. **Bidirectional Encoder Representations from Transformers (BERTopic):** Leveraged for topic modeling and deep learning, providing insights into prevalent themes in NLP applications.

## Data
Data was collected from r/prochoice and r/prolife from January 2022 to March 2023. The data was divided into quarterly segments for sentiment analysis based on the timeline. Key data points include comments, date, post upvotes, and comment upvotes.

## Analysis
The analysis was conducted in four phases:

1. **Data Gathering and Cross-Validation:** Ensured accurate and relevant data retrieval from Reddit communities, cleaning redundant data, and validating fetched data.
2. **Sentiment Analysis and Visualization:** Utilized VADER model for sentiment analysis and visualized sentiment distribution.
3. **Timeline Sentiment Analysis:** Analyzed sentiment distribution over timeframes to understand sentiment evolution.
4. **Topic Modelling:** Identified prominent themes using LDA model, further refined using BERTopic for precise theme assignment.

## Results
### Key Findings:
1. **Sentiment Distribution:** Both communities predominantly expressed negative sentiments, with r/prolife showing an increase in positive comments over time.
2. **Attitude Comparison:** r/prolife exhibited a slightly higher percentage of negative comments compared to r/prochoice.
3. **Changes in Views:** Comments from r/prolife initially displayed more negative sentiments but transitioned to more positive sentiments over time.
4. **Frequently Used Words:** Word clouds revealed prevalent keywords in both communities' comments, reflecting their core discussions.
5. **Common Themes:** BERTopic identified themes such as 'human women life' in pro-choice comments and 'abortion pro life' in pro-life comments.

## Conclusion
The study highlights the disparities in opinions between the r/prochoice and r/prolife communities regarding abortion. Despite limitations such as potential bias and external factors influencing sentiments, the analysis provides insights into prevailing attitudes, trends, and themes within these communities.
