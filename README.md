# Anime vs. Manga Analysis

## Overview
This project aims to analyze and compare anime and manga series from MyAnimeList (MAL) to answer the question: "Is anime more popular and well-received than manga?" To address this question, we perform exploratory data analysis (EDA) on a dataset containing information about the top 10,000 anime and manga series from MAL.

## Table of Contents
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Exploratory Data Analysis (EDA)](#eda)
- [Seasonality Analysis](#seasonality-analysis)
- [Yearly Trends](#yearly-trends)
- [Lifespan Analysis](#lifespan-analysis)
- [Comparative Analysis](#comparative-analysis)
- [Statistical Testing](#statistical-testing)
- [Conclusions](#conclusions)

## Dataset
The dataset used in this analysis consists of information about anime and manga series, including titles, scores, votes, rankings, popularity, start and end dates, and types (anime or manga). The data was collected from the top 10,000 entries on MAL.

## Preprocessing
In the preprocessing step, we performed the following tasks:
- Converted date strings to datetime objects for analysis.
- Handled missing values and data inconsistencies.
- Created a unified DataFrame for both anime and manga series.
- Removed duplicate entries to ensure data integrity.

## Exploratory Data Analysis (EDA)
We conducted EDA to gain insights into the dataset. Key visualizations and analyses include:
- Histograms comparing the distribution of scores for anime and manga.
- Seasonality analysis to determine the average score and popularity by season.
- Yearly trends in average scores for both anime and manga.
- Lifespan analysis to examine how the duration of series impacts their scores and popularity.

## Seasonality Analysis
We investigated the effect of season on the popularity and scores of anime and manga. Surprisingly, the results revealed seasonal patterns that challenged our initial assumptions.

## Yearly Trends
We explored the yearly trends in average scores for both anime and manga. This analysis provided insights into how the quality of series has evolved over the years.

## Lifespan Analysis
To understand whether series with shorter or longer durations perform differently, we categorized them into lifespan categories (e.g., 0-3 months, 1-3 years) and analyzed the average scores and popularity for each category.

## Comparative Analysis
We compared anime and manga series with the same titles to identify differences in scores, popularity, and votes.

## Statistical Testing
We conducted t-tests to determine if there are statistically significant differences in scores and popularity between anime and manga.

## Conclusions
Our analysis provides valuable insights into the popularity and reception of anime and manga on MAL. The results challenge some preconceptions about the two mediums and offer a nuanced perspective on their respective strengths and weaknesses.

Feel free to explore the code and visualizations in this repository to gain a deeper understanding of the findings.

## Acknowledgments
This project was made possible with the support of the Python programming language, pandas, matplotlib, and scipy libraries.