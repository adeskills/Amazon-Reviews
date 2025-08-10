Amazon Customer Reviews – Unsupervised Machine Learning Analysis

Project Overview
Amazon is one of the largest e-commerce platforms in the world, receiving millions of product reviews across diverse categories.

These reviews provide critical feedback on user experiences, revealing valuable information about:

User sentiment toward Amazon services and products

Key likes and dislikes expressed in feedback

Trends in satisfaction over time

Recurring issues in negative reviews

Customer loyalty and likelihood to recommend, based on Net Promoter Score (NPS)

This project applies unsupervised machine learning techniques to analyze user reviews for Amazon's digital software products, uncovering patterns and actionable insights without relying on labeled training data.

Project Goals

The primary objectives are to:

Understand user sentiment from text reviews and ratings.

Identify common topics and themes in positive and negative reviews.

Track sentiment trends over time to detect changes in customer satisfaction.

Pinpoint recurring issues that drive negative feedback.

Estimate customer loyalty using NPS segmentation (Promoters, Passives, Detractors).

Dataset

The dataset contains Amazon product review records with the following key features:

Feature	Description

marketplace---Country of marketplace (US)

customer_id---Unique customer identifier

review_id---Unique review identifier

product_id---Unique product identifier

product_parent---Grouping of related products

product_title---Name/title of the product

product_category--Product category (digital software)

star_rating---Rating score (1–5)

helpful_votes---Number of helpful votes

total_votes---Total number of votes

vine---Indicates if the review is part of the Vine program

verified_purchase---Indicates if the purchase was verified

review_headline---Summary headline of the review

review_body---Main content of the review

review_date---Date when the review was posted

Note: All data is anonymized and provided in compliance with Amazon’s data usage policies.

Methodology

Data Cleaning & Preprocessing

Remove duplicates and handle missing values

Normalize text (lowercasing, removing special characters, tokenization)

Handle imbalanced helpful/total votes

Exploratory Data Analysis (EDA)

Distribution of ratings and votes

Trends over time

Relationship between review length, rating, and helpfulness

Text Analysis & Feature Extraction

Tokenization and lemmatization

TF-IDF and word embeddings for text representation

Unsupervised Learning

Topic modeling (LDA / NMF) to extract common review themes

Clustering reviews based on sentiment and topics

Sentiment Analysis

Rule-based or lexicon-based sentiment scoring (VADER/TextBlob)

Aggregation of sentiment over time

NPS Estimation

Classify customers as Promoters, Passives, or Detractors

Analyze NPS trends and drivers of loyalty

Expected Outcomes

Top recurring themes in positive and negative feedback

Sentiment trend charts over months/years

Word clouds for common positive vs. negative keywords

NPS breakdown showing loyalty distribution

Insights to improve customer satisfaction and retention

Potential Impact

Customer Experience Improvement – Identify pain points and address them proactively.

Product Development – Align product updates with customer needs and preferences.

Brand Reputation Monitoring – Detect emerging issues before they escalate.

Retention Strategy – Boost NPS by resolving detractor pain points.

