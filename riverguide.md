---
title: The New Zealand RiverGuide
seo:
  title: ''
  description: ''
  robots: []
  extra: []
  type: stackbit_page_meta
layout: page
---
*April 23 2021*

{: style="text-align: justify" }

The New Zealand RiverGuide was developed to provide live environmental data alongside recreational guides for activities in New Zealand freshwater. It also provides functionality for users to edit descriptions, post public notices and log their activities. This was a personal project in a collaboration with an environmental scientist with a vision to both share and collect data about freshwater recreation in New Zealand.

The live website, <https://riverguide.co.nz/,> has been public for over a year and has hundreds of unique visitors every week.

The hosting costs of the website and back-end services are supported by White Water New Zealand, who have taken over ownership of the platform going forward. I continue to develop improvements and maintain the services.

![](/images/Screenshot%20from%202021-04-23%2022-50-58.png)

{: style="text-align: justify" }

The RiverGuide has three main components, each a separate software project.

The front end is the RiverGuide itself, a React application written in TypeScript. The code is available here:

<https://github.com/JamesHMcKay/RiverGuide>

{: style="text-align: justify" }

The RiverGuide is the only website that presents live river flow and rainfall gauges from all New Zealand regional councils in one place. This collection of data from 15 different sources is  delievered using a custom built backend service, the [RiverService](https://github.com/JamesHMcKay/RiverService). This application is effectively a high performance data pipeline, it automatically collects live data, cleans the data and makes it consistent. This service makes all New Zealand's rainfall and flow data available through a REST API for the RiverGuide to display in a user friendly way.
