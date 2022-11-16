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

### Why did I choose this topic for my project?

Coronavirus disease (COVID-19) is an infectious disease caused by the SARS-CoV-2 virus. 

If infected with the virus, you may experience mild to moderate respiratory illness and recover without requiring special treatment. However, some will become seriously ill and require medical attention. Cornoavirus affects all ages and affects individuals differently depending on factors such as age, lifestyles and health etc.

The main reason for choosing this dataset is because **COVID-19** was and still is a huge part of all our lives, due to it being a global disease, and I wanted a dataset that I would feel passionate about digging into and the **"covid19_open_data".** I have selected on BigQuery allows me to analyse and compare factors that increased the chances of more individuals dying or catching the disease, such as, the more schools closed, did fewer people die due to the disease.

## Obtaining Data

Where did I find my data set
Why did I choose the data set
Why did I use the platform eg BigQuery 
Video link?

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

### Why did I choose my data?

### Why did I use BigQuery to get my data?

I was looking for an up-to-date dataset that would allow my project to be accurate. In the last 12 weeks I have learnt that BigQuery is regularly updated, so my code and chart will update automatically when I run the code. 
[BigQuery](https://console.cloud.google.com/bigquery) isn't just fast but also highly suitable for running complex analytical queries on large data sets, such as the Covid-19 data set I have chosen. If I had used Kaggle instead, I would of had to do all my coding on [Deepnote](https://deepnote.com/) which struggles to handle large datasets. Therefore, it was clear to me from the start that I should use [BigQuery](https://console.cloud.google.com/bigquery)  for the majority of my project.

## Tech Stack

For my project, I have chosen the following stacks:

## Data Exploration
 
Import all my code to Github

## Data Cleaning 

Import all my code to Github that I have cleaned
Explain what I have done and why?

## Visual Analysis

Import all my graphs and charts to Github

## Conclusion 

