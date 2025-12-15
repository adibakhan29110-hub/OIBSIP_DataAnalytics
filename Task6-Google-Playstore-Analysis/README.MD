Task 6: Unveiling the Android App Market
Analyzing Google Play Store Data
 Overview

This project explores the Google Play Store ecosystem using data analytics and visualization techniques. The goal is to understand app market dynamics, including category distribution, ratings, popularity, pricing trends, and user sentiment.

The analysis focuses on cleaning data, extracting meaningful insights, and visualizing patterns to support data-driven decision-making.

Objectives

Clean and preprocess Google Play Store data

Analyze app distribution across categories

Study ratings, reviews, pricing, and popularity trends

Perform basic sentiment analysis on user reviews

Generate insightful visualizations

Enhance interpretation using data visualization principles

 Project Structure
Task6-Google-Playstore-Analysis/
├── data
│   ├── raw
│   │   └── googleplaystore_small.csv
│   └── cleaned
│       └── googleplaystore_cleaned.csv
│
├── notebooks
│   └── Google_Playstore_Analysis.ipynb
│
├── reports
│   ├── figures
│   │   ├── category_distribution.png
│   │   ├── rating_distribution.png
│   │   ├── free_vs_paid.png
│   │   └── reviews_vs_ratings.png
│   └── report.md
│
└── README.md

🧹 Data Preparation

Removed missing and invalid values

Corrected data types for:

Ratings

Reviews

App size

Price

Filtered a smaller dataset to comply with GitHub file size limits

Key Analysis Performed
Category Exploration

Distribution of apps across categories

Identification of dominant app categories

Metrics Analysis

Rating distribution

Review counts vs ratings

Free vs paid app comparison

Sentiment Analysis

Basic sentiment polarity analysis on user reviews

Identification of positive and negative feedback trends

Visualizations

All plots are saved in reports/figures:

App distribution by category

Rating distribution histogram

Free vs paid apps pie chart

Reviews vs ratings scatter plot

These visuals help communicate insights clearly and effectively.

🛠️ Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Key Insights

Most apps are concentrated in a few major categories

Free apps dominate the Play Store

Higher review counts generally correlate with higher visibility

Ratings cluster around the 4–4.5 range

Conclusion

This project demonstrates how data analytics and visualization can uncover valuable insights into the Android app market. The findings can help developers, marketers, and analysts better understand app performance and user behavior.

Author

Adiba Khan