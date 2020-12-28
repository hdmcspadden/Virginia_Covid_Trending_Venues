# Virginia Covid Trending Venues
Used for IBM Data Science Capstone project, this repository contains work towards analysis of trending business venues in Virginia zip codes with high covid transmission per capita as of December 2020.

## Data Sources
Data Sources are:
* **World Population Review Population by Virginia Zip Code** (https://worldpopulationreview.com/zips/virginia):
  * Virginia zip code
  * Estimated 2020 population per zip code
  
* **Virginia Open Data Portal COVID-19 Counts by Zip Code** (https://data.virginia.gov/Government/VDH-COVID-19-PublicUseDataset-ZIPCode/8bkr-zfqv)
  * Virginia Zip Code
  * Date (5/15/2020 - 12/27/2020)
  * COVID-19 Case Count (cummulative)
  
* **FourSquare Venues Endpoint** (https://developer.foursquare.com/docs/places-api/endpoints/)
Use trending venues, collected from several times over several days to get a good picture of current trending venues.
  * Venue ID
  * Name
  * Location
  * Categories

Will use venue categories to determine whether specific venue categories in a zip code are correlated with higher per capita covid COVID rates in that zip code. This analysis is limited because we know that people travel to venues outside their residential zip code.


