# Yelp Dataset SQL Analysis

## Project Overview

This project is a structured SQL-based analysis of the Yelp dataset, completed as part of a data science coursework assignment. The goal was to explore, profile, and analyze real-world business and user data using SQL in order to answer both guided and self-directed analytical questions.

The dataset includes information on businesses, reviews, users, tips, check-ins, and related attributes. The analysis focuses on understanding data structure, identifying patterns, and drawing insights from user behavior and business performance.

---

## Objectives

This project is divided into two main parts:

### Part 1: Data Profiling & Exploration
- Understand dataset structure across multiple tables
- Count and validate records in each table
- Identify primary and foreign key distributions
- Check for missing or null values
- Calculate minimum, maximum, and average values
- Perform basic SQL aggregations and grouping

### Part 2: Data Analysis & Insights
- Compare business ratings across cities and categories
- Analyze relationships between reviews, ratings, and user engagement
- Explore differences between open and closed businesses
- Perform custom analysis on user behavior

---

## Tools & Technologies Used

- SQL (SQLite / MySQL style syntax)
- Yelp Academic Dataset
- Text editor for query execution and documentation

---

## Key Analysis Summary

### Data Profiling
- Verified record counts across all major tables
- Validated key distributions (businesses, users, reviews, etc.)
- Confirmed no missing values in the user table
- Calculated descriptive statistics for ratings and engagement metrics

### Business Insights
- Identified cities with the highest review volumes (Las Vegas ranked highest)
- Compared star rating distributions across different locations
- Observed variation in business popularity by geography

### User Behavior Insights
- Ranked users by review count and number of fans
- Found weak correlation between review count and fan count
- Identified that tenure on Yelp influences user popularity more than activity volume alone

### Sentiment Analysis
- Reviews containing the word "love" appear significantly more often than "hate"
- Indicates overall positive sentiment bias in the dataset

---

## Key Findings

- Large metropolitan areas dominate total review volume
- User influence is strongly tied to longevity rather than just activity
- Higher-rated businesses tend to cluster in specific geographic regions
- Open businesses show stronger engagement patterns than closed ones

---

## Custom Analysis Summary

A custom dataset was created to analyze experienced Yelp users and their engagement patterns.

### Focus Areas:
- Years active on Yelp
- Average star ratings
- Total review count
- Total compliments received

### Insight:
Long-term users tend to accumulate significantly more engagement and recognition, suggesting that consistency and tenure play a key role in user influence on the platform.

---

## Project Structure

/yelp-sql-analysis
├── queries.sql
├── analysis.sql
└── notes.txt

---

## Notes

- All SQL queries were written for clarity and readability
- Outputs were validated directly from query results
- Formatting was used to ensure reproducibility of analysis

---

## Author
Ross Schanck  
M.S. Data Science
