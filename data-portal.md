---
title: COVID-19 Data Portal
seo:
  title: ''
  description: ''
  robots: []
  extra: []
  type: stackbit_page_meta
layout: page
---
### Media

CIO Magazine: [https://www.cio.com/article/3567928/how-stats-nz-democratised-the-use-of-data.html](https://www.cio.com/article/3567928/how-stats-nz-democratised-the-use-of-data.htmlSoftwareShiny)

### Software

<https://github.com/StatisticsNZ/data_portal>

### Background

As New Zealand entered a lock down to prevent the spread of COVID-19 there was a need from both the public and private sectors for accessible, up to date data. With so many data sets available, and coming in fast, we wanted to produce something to get data out as quickly as possible.

![](/images/Screenshot%20from%202021-04-26%2023-15-37.png)

As the economic and social situation in New Zealand rapidly changed, we were collecting more and more data from a range of sources. We needed a robust system for combining this data together and getting out to the public, while maintaining a high standard of publishing and a zero tolerance for errors.

### Software solution

With a technology stack limited to R and a server that could host Shiny R applications, I developed a solution for data ingestion and standardisation through to presentation in a consistent, clean format. From an initial dozen indicators, we scaled to hundreds over the months during and after the New Zealand lock down. At the time of writing the product is still in operation a year on.

The key part of the solution was an ingestion layer. I created the ability to define a small, custom, R function to ingest each data set. With new data sets constantly arriving, and being updated daily, we needed a system to handle all the different formats. Once these functions are defined, if the data format doesn't change, it's set and forget for future updates. If it does change, it's no hassle to go in a tweak the ingestion layer for that data set.

With all data sets ingested and converted into a consistent structure, the rest of the application is simple, with only a small number of predefined plot functions required to present hundreds of data sets.

This approach was key, and enabled a product to be delivered fast and with minimal burden on data suppliers.

### Data visualisation

Simplicity is essential when presenting large, disparate and constantly evolving data sets. While fancy dashboards with all the bells and whistles are nice, they simply can't be maintained or scaled. The COVID-19 Data Portal used simple, consistent chart styles, with only a half dozen or so different chart types. Configuration was used to tweak these, but overall consistency was maintained.





