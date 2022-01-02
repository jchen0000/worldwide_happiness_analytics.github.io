Proposal
================

Jiaqi Chen (jc5681), Xinran Sun (xs2447), Yiru Gong (yg2832), Yunlin
Zhou (yz4184)

### The tentative project title

World Happiness’ Relationship to Social Factors

### The motivation for this project

We chose this dataset because we want to analyze what factors affect
people’s happiness scores. Factors that are included into our
consideration are country, year, GDP, healthy life expectancy at birth,
freedom to make life choices, generosity, and perceptions of corruption.
Our goal is to find out both direct and inverse relationships between
people’s heappiness and above factors.

### The intended final products

A website will be built to present our analysis and conclusion derived
from the World Happiness Report data. On this website, first, people
could read the background of the World Happiness Report. We would like
to focus on which factors contribute most to people’s happiness. Second,
there would be questions that arose during our process of analyzing the
data on the website. Third, we would use plots and other formats to best
conclude our result. Finally, we would discuss our findings and our
expectations.

### The anticipated data sources

We downloaded this dataset from [World Happiness
Report](https://worldhappiness.report/ed/2021/#appendices-and-data).

``` r
library(readxl)
happiness_data = read_excel("DataPanelWHR2021C2.xls")
```

### The planned analyses / visualizations / coding challenges

We will first visualize the global happiness score distribution with a
world map and a bar plot of happiness rank. Besides, a yearly alteration
line plot will be presented. Then we will investigate the relationship
between happiness score and GDP, social support, life expectancy,
freedom score to make life choices, Generosity, Perceptions of
corruption, and scatter plots with fitted curve will be plotted. All
plots will be presented by `plotly` interactive plots to ensure
readability. The coding challenges remains in data cleaning,
visualizing, and relationship analyzing.

### The planned timeline

-   November 16-19: Project Review Meeting
-   November 20-26: Writing Scripts
-   November 27-December 3: Report
-   December 4-10: Webpage and screencast
