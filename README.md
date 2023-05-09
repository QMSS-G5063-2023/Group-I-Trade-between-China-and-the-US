# Group-I-Trade-between-China-and-the-US
### Solar Photovoltaic Trade Between China and the US
## Abstract: 
We are interested in understanding the trade trend between China and the US, specifically after Covid-19 took place in 2020. We will focus only on solar panel trade, as it has been a crucial business between these two superpowers. We will make use of the dataset from department of energy, solar energy research database and LexisNexis text data from Columbia library to explore this question from import-export perspective, solar-factory perspective, and activeness of solar power labs:

• Import-Export: How does the trend of importing solar panels from China to the US indicate about the international relationship between the two countries after Covid-19? We expect the trend to continue growing despite the worsening relationship.

• Solar-Factory: Which American factories are solar panels shipped to? What are the determinants of the solar panel factory locations? Are there any differences in factory locations throughout a span of 3 years (2020, 2021, 2022)?

• Activeness of Solar Power Labs: Based on the solar projects throughout the US, which planetaries remains active after 2020? What is the average duration of active solar panel labs based on different locations?

• Trade Relationship Between China and the US: How has the sentiment towards the solar panel trade relationship changed from journals? What are the key words when it comes to trade between China and the US after 2020?

## Techniques: ggplot2, ggmap, NLP text mining, Shiny, interaction

## Data Description:
• Dataset: https://www.energy.gov/eere/solar/solar-energy-research-database

o The data is from office of energy efficiency & renewable energy that lists all the solar energy projects at national laboratories, state and local governments, universities, nonprofit organizations, and private companies to improve solar technologies.

o It includes all the active and inactive projects, locations, start dates, funding opportunity and program area.

• Dataset: https://library.columbia.edu/help/howto/elink/fulltextln.html

o We will web scrape sentiment data from Columbia library with keywords such as ‘solar panels’, ‘trade’, ‘China’, etc. This will help us understand the trade relationship between China and the US, and whether it is maintaining a positive or negative relationship, and the causes of negative relationship if there is any.

o The visualization will be word cloud and pyramid plot.

• Dataset: https://catalog.data.gov/organization/doegov?capacity=public&tags=solarnhj%20uu

o This dataset includes solar photovoltaic R&D labs. It is a large-scale time-series database containing system metadata and performance data from a variety of experimental PV sites and commercial public PV sites.

## Visualizations:
• Map: We will use ggmap to illustrate the export and import of solar panels from China to US and from US to China. We will also use ggmap to visualize the planetary locations in the US.

• Word Cloud: We will get the most frequent words about solar trade between the US and China through web scraping to see the positive and negative sentiment towards the trade.

• Bar Chart: We could use bar chart to visualize the trend of import and export amount for solar panels throughout 2020, 2021 and 2022.

• Line Chart: We could use line chart to illustrate the change of trade balance between China nd the US over 2017-2021.

