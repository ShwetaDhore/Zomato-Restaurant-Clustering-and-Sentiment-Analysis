# Zomato-Restaurant-Clustering-and-Sentiment-Analysis
![Zomato-logo](https://github.com/user-attachments/assets/da857edf-b525-4a3d-a615-fb8a55b25e3f)
The project centers around understanding the dynamics between customers and the company, delving into the sentiments expressed in customer reviews and drawing actionable insights through visualizations. By clustering Zomato restaurants into distinct segments, we aim to provide clarity in restaurant choices for customers while offering strategic directions for the company's growth and areas of improvement.

Visualizations play a pivotal role in simplifying data analysis, allowing for instantaneous comprehension. Through sentiment analysis of customer reviews, we can derive meaningful conclusions and address business cases, facilitating informed decision-making for both customers seeking the best dining experiences and the company's strategic advancements.

Moreover, leveraging rich data on cuisine varieties and pricing enables us to conduct cost-benefit analyses, aiding in identifying optimal strategies for business expansion.

This comprehensive approach not only facilitates restaurant clustering but also empowers us to identify industry influencers and critics through the metadata of reviewers, enriching our understanding of market dynamics and customer preferences.

# Zomato Restaurant Clustering and Sentiment Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Collection](#data-collection)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Clustering](#clustering)
- [Sentiment Analysis](#sentiment-analysis)
- [Model Evaluation](#model-evaluation)
- [Installation and Usage](#installation-and-usage)
- [Results](#results)
  

## Project Overview
This project aims to analyze Zomato restaurant data by clustering similar restaurants and performing sentiment analysis on customer reviews. The objective is to provide insights into restaurant types and customer sentiment trends.

## Data Collection
The data used in this project is sourced from the Zomato API and includes information about restaurants, such as:
- Restaurant name
- Location
- Cuisine type
- Average cost for two
- Ratings
- Reviews

## Data Preprocessing
Data preprocessing steps include:
- Handling missing values
- Normalizing numerical features
- Encoding categorical features
- Text preprocessing for reviews (tokenization, stop words removal, etc.)

## Exploratory Data Analysis (EDA)
EDA is performed to understand the distribution and relationships of various features in the dataset. Key analyses include:
- Distribution of restaurant ratings
- Average cost for different cuisine types
- Location-based analysis

## Clustering
Clustering is used to group similar restaurants based on features such as cuisine type, average cost, and ratings. Techniques used:
- K-Means Clustering
- Evaluation of cluster quality using metrics like silhouette score

## Sentiment Analysis
Sentiment analysis is performed on customer reviews to gauge overall customer satisfaction. Steps include:
- Text vectorization (using TF-IDF or word embeddings)
- Sentiment classification (using models like Logistic Regression, SVM, or LSTM)
## Conclusion

The project was successful in achieving the goals of clustering and sentiment analysis. The clustering part provided insights into the grouping of restaurants based on their features, which can help in decision making for users and businesses. The sentiment analysis part provided insights into the sentiments expressed by the users in their reviews, which can help businesses in improving their services and user experience.

There are several potential areas for future work, such as implementing more advanced clustering algorithms and sentiment analysis techniques, incorporating more features such as images and menus of the restaurants, and exploring the relationships between the clustering and sentiment analysis results.Write the conclusion here.

