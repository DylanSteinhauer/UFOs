# UFOs
## Purpose
The purpose of this challenge was to use Javascript, HTML, and d3 to create an interactive webpage containing UFO sightings that can be filtered by
date, city, state, country, and shape.
## Results
![filters](https://user-images.githubusercontent.com/87148177/138607330-6d2a84a6-4c26-4401-a233-ea0452288c34.png)\
There are five filters you can use for your search; and you can use any combination of these filters to narrow down the results. 
For the state and country filters, you must use the two letter abbreviation associated with them. For example, New Mexico is abbreviated as 'nm'.\
![search_example](https://user-images.githubusercontent.com/87148177/138607543-0704b107-84ae-4a72-8fcf-8bf512441c60.png)\
Here is an example using the filters. When we filter by California and the "formation" shaped UFO, it returns two sightings. 
Both sightings were reported as three red lights seen high in the sky.
## Summary
One drawback of this design is that you can only search for sightings on specific days, rather than ranges. Searching by time ranges could allow for more in depth interpretation of the data.
Because of this, my first recommendation would to modify the Date filter into a Date Range filter so that users can search sightings within a certain timeframe.
In addition, I would recommend adding another filter for the duration of the sighting, since this information is already in the tables. This filter could also take in range queries, such as searching for sightings that were < 10 minutes or between 10-20 minutes for example.
