# Project Proposal: Impact of Market Share on Flight Operational Performance

## 1. Motivation
In the aviation industry, operational efficiency is a primary determinant of passenger satisfaction and airline reputation. This project aims to investigate the relationship between market dynamics—specifically an airline's market share on a given route—and its operational reliability, such as flight delays. The core objective is to analyze whether dominant airlines on specific routes maintain better punctuality or if a lack of competition correlates with increased operational delays.
In the avation indusrty

## 2. Data Source and Collection
The study will utilize two publicly available datasets sourced from Kaggle:
* **Dataset 1 (Operations):** "Flight Delay and Cancellation Data (2024)" which contains over 1 million rows of flight-level data, including origin, destination, delay minutes, and categorized delay causes.
* **Dataset 2 (Pricing/Market):** "US Airline Flight Routes and Fares (1993-2024)" providing route-level information such as average fares, total number of passengers, and market share percentages per airline.

The data will be retrieved directly from Kaggle.

## 3. Data Characteristics and Enrichment
The primary dataset provides operational details but lacks market context. To satisfy the project's enrichment the operational data will be enriched by joining it with the second dataset based on "Origin" and "Destination" pairs (Route level). This integration allows for the mapping of each flight’s delay performance to the specific airline’s market share and average pricing on that route.

## 4. Planned Techniques and Analysis
The project will follow the standard data science pipeline:
* **Data Preparation:** Cleaning missing values and merging datasets via Python.
* **Exploratory Data Analysis:** Visualizing delay distributions across different airlines and routes using Matplotlib and Seaborn.
* **Hypothesis Testing:** Performing statistical tests to determine if there is a significant difference in delay averages between "dominant" and "competitive" routes.
