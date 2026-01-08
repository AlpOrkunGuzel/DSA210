# Project Title
**The Economics of Olympic Success: How GDP and Population Shape Medal Performance**

# Motivation

The Olympic Games are widely regarded as a symbol of international unity and athletic excellence. However, behind the spectacle of competition lies a recurring question: do wealthier nations inherently perform better than others? This project investigates whether economic strength and population size are associated with Olympic success.

Using data from recent decades of Olympic history, the study examines whether a country’s economic indicators—particularly Gross Domestic Product (GDP), GDP per capita, and population size—are correlated with its Olympic performance. The primary goal is to identify measurable patterns that explain how economic prosperity and demographic scale influence athletic success, and to highlight countries that outperform or underperform relative to their economic standing.

# Data to Use

This study integrates two main datasets. The first dataset is the “120 Years of Olympic History: Athletes and Results” dataset (https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results), available publicly on Kaggle. It contains detailed records of every Olympic athlete from 1896 to 2020, including fields such as National Olympic Comittee (NOC), year, sport, event, and medal type. For this project, the data was aggregated to the country–year level. Medal counts were computed by summing gold, silver, and bronze medals for each country in a given Olympic Games. This dataset provides the main measure of Olympic success.

The second dataset comes from the World Bank Open Data platform (https://data.worldbank.org/). It includes macroeconomic indicators for most countries. In this project, three variables were used:

* total GDP (current US$)
* GDP per capita (current US$)
* total population

These indicators represent the economic size and development level of countries and are used to examine their relationship with Olympic performance.

**Note:** Due to GitHub file size limitations, the full Olympic dataset
(`athlete_events.csv`) is not included in this repository.
It can be downloaded directly from Kaggle using the link below:

https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results

# Research Questions

* Is there a relationship between GDP and total Olympic medals?
* Do more populous countries win more medals on average?
* Is GDP per capita associated with higher medal efficiency?

# Methadology / Analysis Plan

1. Data cleaning and preprocessing
2. Aggregating Olympic data to the country–year level
3. Merging Olympic data with World Bank economic indicators
4. Exploratory data analysis and visualization
5. Statistical analysis (correlations and hypothesis testing)
6. Application of machine learning models (PCA, K-Means clustering, and Random Forest regression) to evaluate predictive relationships



