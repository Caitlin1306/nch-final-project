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

## Rationale

## Obtaining Data

### Where did I get my data?

I got my data from a BigQuery public dataset.
I started with exploring my data using standard SQL.
My first query was 
```
SELECT
  MAX(date) as end_date,
  MIN(date) as start_date
FROM
  `bigquery-public-data.covid19_open_data_eu.covid19_open_data`;
```

#### Why did I choose my data?

##### Why did I use BigQuery to get my data?

I was looking for a up to date dataset that would allow my project to be accurate. In the last 12 weeks I have learnt that BigQuery is regularly updated, so my code and chart will update automatically when I run the code. 
BigQuery isn't just accurate, but it is also perfect for running complex analytical queries on large sets of data such as the covid 19 data set I have chosen. If I had used Kaggle instead, I would of had to do all my coding on deepnote which struggles to handle large datasets. Therefore it was clear to me from the start that I should use BigQuery for the majority of my project.

## Tech Stack

## Data Exploration

## Data Cleaning 

## Visual Analysis

## Conclusion 

