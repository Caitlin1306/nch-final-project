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

[Link to my project plan](https://docs.google.com/document/d/1OuMQPu6PXZGiezz-ZZQXcmpNE61Zj6OXMKqFOeeDLMM/edit)

## Introduction

To complete the Data Analytics course at [Northeastern University London](https://www.nulondon.ac.uk/), I had to produce the final project to fulfill the following criteria:

- Provide the project rationale.
- Utilize a minimum of 3 technologies, e.g., [Pandas](https://pandas.pydata.org/docs/), [Plotly](https://plotly.com/python/) & [Standard SQL](https://cloud.google.com/bigquery/docs/reference/standard-sql/introduction)
- Collect feedback, i.e., make pull requests on GitHub, adding @missKatiaPunter  & @T-J-Summer  as reviewers 
- Use data visualization, i.e., bar charts, scatter plots & line charts etc. 
- Document the project in [GitHub](https://docs.github.com/en), [Deepnote](https://deepnote.com/docs), [Google Docs](https://www.google.com/docs/about/) & [Slides.com](https://slides.com/)
- Apply Agile methodologies, i.e., [Kanban Boards](https://github.com/topics/kanban)
- Use some statistical and machine learning analysis
- Reach a conclusion 

## Rationale

### Why did I choose this topic for my project?

Coronavirus disease (COVID-19) is an infectious disease caused by the [SARS-CoV-2](https://www.who.int/emergencies/diseases/novel-coronavirus-2019) virus. 

If infected with the virus, you may experience mild to moderate respiratory illness and recover without You may experience mild to moderate respiratory illness if infected with the virus and recover without requiring special treatment. However, some will become seriously ill and require medical attention. Coronavirus affects all ages and individuals differently depending on factors such as age, lifestyle, health, etc.

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

The main reason for choosing this dataset is because **COVID-19** was and still is a huge part of all our lives due to it being a global disease, and I wanted a dataset that I would feel passionate about digging into and the **"covid19_open_data"** seemed precisely that. I have selected BigQuery as it is a part of [the Google Cloud](https://cloud.google.com/docs) and subsequently very fast. Moreover, it allows me to use [Standard SQL](https://cloud.google.com/bigquery/docs/reference/standard-sql/introduction) to analyse and filter the data before uploading it to a Jupyter notebook. In this project, I wanted to compare the effects of different government response actions, e.g., school closures, transport closures, vaccinations, etc. 

> My ultimate goal was to identify the government response most effectively fighting the pandemic.

## Tech Stack

For my project, I have chosen the following stacks:

- [Standard SQL](https://cloud.google.com/bigquery/docs/reference/standard-sql/introduction)
- [Pandas](https://pandas.pydata.org/docs/)
- [Plotly](https://plotly.com/python/)

## Data Exploration
 
Import all my code to Github

## Data Cleaning 

Import all my code to Github that I have cleaned
Explain what I have done and why?

## Visual Analysis

Import all my graphs and charts to Github

## Conclusion 

