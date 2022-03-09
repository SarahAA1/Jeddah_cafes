# London Restaurants 
By: Sarah Alharbi 

This repository, is the Capstone projectt as a part of Immersive Data Science Course provided by [MISK](https://hub.misk.org.sa).

In this Project, I'm trying to perform multiple analysis in order to choose the most appropriate location for opening a new restaurant in London.



##  Introduction
London is the capital and largest city of England and the United Kingdom, in terms of both area and population. According to [London Datastore](https://data.london.gov.uk/dataset/londons-population), London population in 2020 reached more than 9 Million. It the most populous city in Europe, it ranks 25th populous urban agglomeration of the world and total area is 1580 km².


Therefore, I have chosen London to be my scope for this project due to the data availability and also for the great memories I had there, as well as the diverse culture of London.

## Problem Description

The restaurant's location is crucial since the more populous the area is, the more cutomers will visit. However, It should avoid establishing a cafe in a wrong location or in an area with a large number of competitors. That's way opening a new cafe could be a challinging task, because of that investors may have to think carefully about what would be the right place for their restaurant? 

## Project Questions
- Are particular cuisines/restaurant types more popular in specific borough than others?

- Is it feasible to cluster boroughs or neighbourhoods based on cuisine criteria in London?



## Data Sources

 
- List of London boroughs and population. [Wikipedia](https://en.wikipedia.org/wiki/List_of_London_boroughs)
- Density [Wikipedia](https://en.wikipedia.org/wiki/List_of_English_districts_by_population_density)
- Median Household Income. [2019 Equivilised Paycheck data - CACI](https://www.towerhamlets.gov.uk/Documents/Borough_statistics/Income_poverty_and_welfare/income_2019_l.pdf)

- Number of employees [Office for National Statistics (ONS)](https://data.london.gov.uk/dataset/workplace-employment-industry-borough)
- [London geojson data](https://skgrange.github.io/data.html)</br>

We will be scraping web page from Wikipedia that provides data of London Boroughs for this project by using BeautifulSoup. While, others data are avalibale to download from their sources. Then, we will use the Forsquare API to search for restaurant all around London. 




## References 
 - http://www.citypopulation.de/en/world/agglomerations/

