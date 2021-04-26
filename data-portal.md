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

*   CIO Magazine: <https://www.cio.com/article/3567928/how-stats-nz-democratised-the-use-of-data.html>

### Software

*   <https://github.com/StatisticsNZ/data_portal>

### Background

As New Zealand entered a lock down to prevent the spread of COVID-19 there was a need from both the public and private sectors for accessible, up to date data. With so many data sets available, and coming in fast, there was a need to produce something to get data out as quickly as possible.

![](/images/Screenshot%20from%202021-04-26%2023-15-37.png)



As the economic and social situation in New Zealand rapidly changed, we were rapidly collecting more data from a range of sources. We needed a robust system for combining this data together and getting out to the public, while maintaining a high standard of publishing and a zero tolerance for errors.

### Software solution

With a technology stack limited to R and the Shiny dashboard package, I developed a solution for data ingestion and standardisation through to presentation in a consistent, clean format. From an initial dozen indicators, we scaled to hundreds over the months during and after the New Zealand lock down. At the time of writing the product is still in operation a year on.

The key part of the solution was a ingestion layer.
