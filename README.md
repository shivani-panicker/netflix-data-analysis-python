# Netflix Data Analysis Using Python

## Project Overview

An exploratory data analysis project analyzing Netflix's catalog of 8,807 titles to identify patterns in content type, ratings, directors, actors, countries, release trends, and description sentiment. The project uses Python-based data cleaning, transformation, aggregation, and visualization techniques to extract insights from the dataset.

## Objectives

- Analyze the distribution of Movies and TV Shows.
- Examine ratings distribution across Netflix content.
- Identify the most frequent directors and actors.
- Analyze country-wise content production.
- Explore yearly content release trends.
- Analyze sentiment patterns in Netflix content descriptions.

## Dataset

- **Dataset:** Netflix Titles Dataset
- **Records:** 8,807 titles
- **Coverage:** Movies and TV Shows available in the dataset
- **Key fields:** Title, Type, Director, Cast, Country, Rating, Release Year, Description

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Data analysis and processing |
| Google Colab | Development environment |
| Pandas | Data cleaning, transformation, and analysis |
| NumPy | Numerical operations |
| Matplotlib | Static visualizations |
| Seaborn | Statistical visualizations |
| Plotly | Interactive visualizations |
| EDA | Exploratory data analysis |

## Data Cleaning & Transformation

- Loaded and explored the Netflix dataset.
- Identified and handled missing values in columns such as `director`, `cast`, and `country`.
- Split multi-value columns into individual values.
- Restructured and stacked multi-value fields for analysis.
- Standardized data for aggregation and grouping.
- Created derived data required for visualization and sentiment analysis.

## Data Analysis

The analysis covered the following areas:

- Movies versus TV Shows distribution.
- Content ratings distribution.
- Top directors and actors.
- Country-wise content production.
- Year-wise content release trends.
- Sentiment analysis of content descriptions.

## Dashboard

The project includes static and interactive visualizations created using Matplotlib, Seaborn, and Plotly.

Key visualizations include:

- **Bar Chart:** Movies vs TV Shows comparison.
- **Pie Chart:** Ratings distribution.
- **Horizontal Bar Charts:** Top directors and actors.
- **Bar Chart:** Top content-producing countries.
- **Line Chart:** Year-wise content release trends.
- **Sentiment Analysis:** Sentiment trends from content descriptions.

## Key Insights

### 1. Content Mix

- Netflix's catalog contains **8,807 titles** and is more heavily weighted toward Movies than TV Shows.

### 2. Ratings

- **TV-MA** is the most common rating, with **3,207 titles**.
- **TV-14** follows with **2,160 titles**, while **R** accounts for **799 titles**.
- Family-oriented ratings represent a smaller share of the catalog, including **TV-Y with 307 titles, TV-G with 220, and G with 41**.

### 3. Top Directors

- **Rajiv Chilaka** leads with **22 titles**.
- **Raúl Campos** and **Jan Suter** follow with **18 titles each**.
- **Suhas Kadav** and **Marcus Raboy** have **16 titles each**.

### 4. Country-wise Production

- The **United States** is the largest content-producing country with **3,211 titles**.
- **India** follows with **1,008 titles**.
- The United States has more than three times the number of titles attributed to India, highlighting the strong US representation in the dataset.

### 5. Content Growth

- Both Movies and TV Shows experienced strong growth after 2015.
- Movie releases peaked at **517 titles in 2020**.
- TV Show releases peaked at **397 titles in 2019**.
- Releases declined slightly in 2021, which may be influenced by the dataset's cutoff and the impact of the COVID-19 period.

### 6. Description Sentiment

- Positive sentiment consistently exceeds Negative and Neutral sentiment across the analyzed years.
- In 2019, descriptions included approximately **552 positive, 308 negative, and 170 neutral** classifications.
- The difference between positive and other sentiment categories increased as the catalog expanded.

## Project Structure

```text
Netflix-Data-Analysis-Python/
│
├── Data/
│   └── Netflix Titles Dataset
│
├── Notebook/
│   └── Netflix Data Analysis.ipynb
│
├── Visualizations/
│   └── Generated charts
│
└── README.md
```

## Conclusion

This project demonstrates an end-to-end exploratory data analysis workflow using Python. The analysis shows that Netflix's catalog is predominantly made up of Movies, has a strong concentration of mature-rated content, and is heavily represented by US-produced titles. Content availability expanded significantly after 2015, while sentiment analysis indicates that Netflix descriptions generally use positive-toned language across the years.

