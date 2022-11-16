# NCH Final Project
 
- [Introduction/Project Requirements](#Introduction)
- [Rationale](#Rationale)
- [Obtaining Data](#Obtaining-Data)
- [Tech Stack](#Tech-Stack)
- [Data Exploration](#Data-Exploration)
- [Data Cleaning](#Data-Cleaning)
- [Visual Analysis](#Visual-Analysis)
- [Conclusion](#Conclusion)

## Introduction

To complete the Data Analytics course at Northeastern University, I had to produce the final project to fulfill the following criteria:

- Provide the project rationale.
- Utilizing a minimum of 3 programming languages, e.g., Pandas, Plotly & SQL
- Collect feedbcak ie Make pull requests on GitHub, adding Katia & Theo as reviwers 
- Use data visualization ie bar charts, scatter plots & line charts etc 
- Document the project in GitHub, Deepnote, Google Docs & Slides.com
- Apply Agile methodologies ie Kanban Boards
- Use statistical and machine learning analysis, e.g. :
Hypothesis testing
Comment all code blocks
Present the project
- Reach a conclusion 

## Rationale

## Obtaining Data

### Where did I get my data?

I got my data from a BigQuery public dataset.
I started with exploring my data using standard SQL.
My first query was the one below 👇.
```
SELECT
  MAX(date) as end_date,
  MIN(date) as start_date
FROM
  `bigquery-public-data.covid19_open_data_eu.covid19_open_data`;
```
When I run the query above, I got the following result: 

![Screenshot from Bigquery](data_period_screenshot.png)

#### Why did I choose my data?

##### Why did I use BigQuery to get my data?

I was looking for an up-to-date dataset that would allow my project to be accurate. In the last 12 weeks I have learnt that BigQuery is regularly updated, so my code and chart will update automatically when I run the code. 
[BigQuery](https://console.cloud.google.com/bigquery) isn't just fast but also highly suitable for running complex analytical queries on large data sets, such as the Covid-19 data set I have chosen. If I had used Kaggle instead, I would of had to do all my coding on [Deepnote](https://deepnote.com/) which struggles to handle large datasets. Therefore, it was clear to me from the start that I should use [BigQuery](https://console.cloud.google.com/bigquery)  for the majority of my project.

## Tech Stack

## Data Exploration

## Data Cleaning 

## Visual Analysis

## Conclusion 

