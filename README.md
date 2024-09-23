# Cafe-Rewards-Offers-Maven-Analytics-Challenge

## Project Overview
This project is part of the Maven Analytics Challenge, where participants are tasked with analyzing customer behavior data from a cafe's rewards program. The goal is to develop a data-driven strategy for future promotional messaging and targeting based on the insights gathered from a 30-day test period.

## Challenge Objective
As a Sr. Marketing Analyst at Maven Cafe, your task is to identify key customer segments and develop a data-driven strategy for future promotional messaging & targeting. The results need to be summarized in a report that will be presented to the CMO.

Challenge Link - https://mavenanalytics.io/challenges/maven-rewards-challenge/404c6060-60eb-400f-9bce-c3b9f97e9d5a

## Dataset Description
The data simulates the behavior of Cafe Rewards members over a 30-day period, including their transactions and responses to promotional offers. It is divided into three files:

offers.csv: Details of each offer sent to customers.

customer.csv: Demographic information of each customer.

events.csv: Activity data for each customer, including offer received, viewed, accepted, and transactions.

## Key Insights
The dashboard created in Power BI includes the following sections:

Offers Break-Down: Provides an overview of all offers, revenue generated, average offers completed, and customer events.
Customer Demographics: Segments customers by age, gender, income, and tracks the new members joining trend.

## Project Structure
The repository is organized as follows:

'''Maven-Cafe-Rewards-Challenge/
├── data/
│   ├── raw/                    # Folder containing raw data files
│   │   ├── offers.csv
│   │   ├── demographics.csv
│   │   └── transactions.csv
│   ├── cleaned/                # Folder containing cleaned data files
│   │   ├── offers_cleaned.csv
│   │   ├── demographics_cleaned.csv
│   │   └── transactions_cleaned.csv
├── notebooks/
│   └── data_cleaning.ipynb     # Jupyter notebook for data cleaning and preparation
├── dashboards/
│   └── MavenCafeRewards.pbix   # Power BI dashboard file
└── README.md                   # Project description and instructions
'''


## Getting Started
## Prerequisites

Python 3.x

Jupyter Notebook

Power BI Desktop

## Usage
Data Cleaning
The data cleaning process is documented in the data_cleaning.ipynb notebook. This involves:

Handling missing values.

Filtering relevant data.

Creating additional columns for analysis.

Dashboard Insights

The Power BI dashboard provides a visual summary of the customer behavior and offer effectiveness:

Offers Break-Down: Understand how different offers performed during the 30-day period.

Customer Demographics: Segment customers based on demographics to identify target groups for future offers.

## Conclusion

This project showcases the ability to clean, analyze, and visualize data to support strategic decisions in a marketing context. The insights derived from this analysis can help Maven Cafe optimize its promotional strategies for better customer engagement and increased revenue.
