# Prediction of Zika Outbreaks
by Michelle L. Gill  

## Summary

This is the source code for my third project in the Summer 2016 [Metis Data Science Bootcamp](http://thisismetis.com), which incorporated supervised machine learning, PostgreSQL, and D3 for visualization.

XXXX
iid timeseries data

## Analysis


## Results


## Data Sources

This project made extensive use of external data sources, including data from GitHub repos and that was scraped from various websites.

1. Zika outbreak data was pulled from the CDC Epidemic Prediction Initiative [GitHub repo](https://github.com/cdcepi/zika). My project used data that was pulled on 07/30/2016, which corresponds to commit `d44c5d1ca3af633224c8b8b490b1a3aafa9bcc8e`. A clone of this commit is available [here](https://github.com/mlgill/zika).
2. Latitude and longitude data for Zika outbreaks was pulled from the following: Google Maps API, Scraped from Google Search via four proxies, and scraped from [LatLong](http://www.latlong.net/).
3. Airport location information was scraped from [Falling Rain](http://fallingrain.com).
4. Airport flight schedules were scraped from [FlightRadar24](https://www.flightradar24.com).
5. Worldwide historical weather data was scraped from [Wunderground](https://www.wunderground.com) using closest airport code as the key.
6. *Aedes aegypti* and *Aedes albopictus* occurrences were from [Dryad](http://dx.doi.org/10.5061/dryad.47v3c/1). See references below for manuscripts related to this data.
7. Worldwide population density was from the [NASA Socioeconomic Data and Applications Center (SEDAC)](http://sedac.ciesin.columbia.edu/data/set/gpw-v4-population-density) Gridded Population and Population Density of the World
8. Flight patterns were scraped from [FlightRadar24](http://flightradar24.com), however this data was not incorporated into the model due to time limitations. 
9. GDP and purchase parity adjusted GDP were also scraped. Like the flight pattern data, time limitations prevented this data from being incorporated into the model.

*References for Aedes aegypti and Aedes albopictus occurrences*

> Kraemer MUG, Sinka ME, Duda KA, Mylne A, Shearer FM, Brady OJ, Messina JP, Barker CM, Moore CG, Carvalho RG, Coelho GE, Van Bortel W, Hendrickx G, Schaffner F, Wint GRW, Elyazar IRF, Teng H, Hay SI (2015) The global compendium of Aedes aegypti and Ae. albopictus occurrence. Scientific Data 2(7): 150035. [http://dx.doi.org/10.1038/sdata.2015.35](http://dx.doi.org/10.1038/sdata.2015.35)

> Kraemer MUG, Sinka ME, Duda KA, Mylne A, Shearer FM, Brady OJ, Messina JP, Barker CM, Moore CG, Carvalho RG, Coelho GE, Van Bortel W, Hendrickx G, Schaffner F, Wint GRW, Elyazar IRF, Teng H, Hay SI (2015) Data from: The global compendium of Aedes aegypti and Ae. albopictus occurrence. Dryad Digital Repository. [http://dx.doi.org/10.5061/dryad.47v3c](http://dx.doi.org/10.5061/dryad.47v3c)
