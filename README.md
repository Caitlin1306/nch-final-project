# NCH Final Project
 
- [Introduction/Project Requirements](#Introduction)
- [Rationale](#Rationale)
- [Obtaining Data](#Obtaining-Data)
- [Tech Stack](#Tech-Stack)
- [Data Exploration](#Data-Exploration)
- [Data Cleaning](#Data-Cleaning)
- [Visual Analysis](#Visual-Analysis)
- [Conclusion](#Conclusion)

[Link to my Deepnote](https://deepnote.com/workspace/caitlin1306-5830-b744c156-1215-41b0-afc0-861533a29a82/project/NCH-Bootcamp-f2ebe341-884e-42c0-b194-dc0e178c25ee/notebook/NCH%20Final%20Project%20-8e630e6780274171848330c518ff31c7)

## Introduction

## Rationale

Why did I choose this topic for my project?

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

#### Why did I choose my data?

##### Why did I use BigQuery to get my data?

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

