# python-api-challenge
Python API Challenge #6 Olga Petrova

There is a very weak negative correlation between temperature and latitude. We might want to look at other graphs for more insight.
There is a very weak positive correlation between humidity and latitude, also suggesting a randomness.
There is a weak positive correlation between cloudiness and latitude.
There is a very weak negative correlation between wind speed and latitude.
Comparing graphs for Northern and Southern Hemispheres, there is a strong indication of temperature increasing when approaching 0 Latitude (Equator). The most cold places are in both poles.
Comparing graphs for Northern and Southern Hemispheres, there is a strong correlation between high humidity and latitude approaching 0. The most humid places are around the Equator, and both poles are the most dry places.
There is no strong correlation with cloudiness, when observing graphs for 2 hemispheres.
With wind statistics - it looks like it’s more windy in Antarctica compared to the Equator. Very weak wind correlation for the Northern Hemisphere.

In general with latitudes between -35 and 35 climate is more mild - with temperatures between 15 to 30 C. With latitudes -20 to 20 temperatures are between 20 C to 30 C, but with a chance of higher humidity.
For people who prefer colder climates, but don’t like the wind, the Northern Hemisphere with latitudes less than 35 is more pleasant. 
For adventurous spirited people, who don’t mind high winds and low temperatures, these graphs are not important. 


_______________________________________________________________
In WeatherPy file while parsing API, there were some inconsistencies with "Sys" part, where "Country" is stored. Ideally Sys supposed to show Country, Sunset and Sunrise, per documentation, but sometimes shows only one parameter. Therefore in some cases Country parameter could be missing.

In VacationPy "Radius" search for hotels shows inconsistent results, in some cases it doesn't show any hotels. Maybe some other searches are better, like finding nearest hotel, instead of 10000 m radius.