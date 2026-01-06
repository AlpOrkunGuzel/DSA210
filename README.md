# The Economics of Olympic Success: How GDP and Population Shape Medal Performance
DSA210 Term Project

Student: Alp Orkun Güzel
Student Number: 34524

## Project Proposal

The Olympic Games are widely regarded as a symbol of international unity and athletic excellence. However, behind the spectacle of competition lies a recurring question: do wealthier nations inherently perform better than others? This project, titled “The Economics of Olympic Success: How GDP and Population Shape Medal Performance,” aims to explore the relationship between a country’s economic power and its Olympic achievements.

By analyzing data from the last few decades of Olympic history, the study will investigate whether a country’s economic indicators—particularly its Gross Domestic Product (GDP), GDP per capita, and population size—correlate with the number of medals it wins. The project’s primary goal is to identify measurable patterns that explain how economic prosperity influences athletic success and to highlight nations that outperform or underperform relative to their economic standing.

## Data to Use

This study will integrate two main datasets. The first dataset is the “120 Years of Olympic History: Athletes and Results” dataset, available publicly on Kaggle. It contains detailed records of every Olympic athlete from 1896 to 2020, including fields such as country (NOC), year, sport, event, and medal type. For this project, only the aggregated country-level and year-level information will be used. Medal counts will be calculated for each country by summing all gold, silver, and bronze medals for a given year. This dataset serves as the foundation of the analysis, representing the measure of Olympic success.

The second dataset will come from the World Bank Open Data platform, which provides reliable macroeconomic indicators for most countries. Specifically, three variables will be used: total GDP (current USD), GDP per capita (current USD), and total population.

## How to Collect the Data

The data collection process will begin with downloading the Olympic dataset from Kaggle and importing it into Python using the pandas library. The data will first be cleaned by removing duplicate entries, standardizing country codes, and handling missing medal information. The next step will be to aggregate the data by country and year, producing a table of total medals for each Olympic cycle.

For the economic data, the wbdata API will be used to query World Bank indicators. Using Python scripts, I will fetch GDP, GDP per capita, and population data for the same time period covered in the Olympic dataset. After retrieving the data, I will clean and reformat it so that the time frames and country names match the Olympic data. Once both datasets are ready, I will merge them on the shared attributes of country and year.


