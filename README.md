# Bay Wheels Geospatial Analysis using Geoplotlib 
Bay Wheels, bike sharing facility started by Lyft in June 2019 focusing in the San Francisco Bay Area. https://www.lyft.com/blog/posts/introducing-bay-wheels-new-bikes-and-a-new-name.

## Data Source
Data is sourced for the two souncred mentioned below and combined into a single dataframe. As the resulting combined dataset is fairly large, a randomly sampled 2% of the data is chosen.
1. Kaggle Website: https://www.kaggle.com/jolasa/bay-area-bike-sharing-trips Kaggle dataset is used in conjunction with a larger dataset from Lyft’s website. Timeperiod January to May 2019
2. Lyft website: https://www.lyft.com/bikes/bay-wheels/system-data From the Lyft dataset a table of unique station information is derived, to pull in geographic data(latitude, longitude) for the beginning and end of each trip.

## GeoPlotLib
A python toolbox for visualizing geographical data. For more detailes on this library, check out this repo: https://github.com/sheetalkalburgi/geoplotlib-geospatial-visualization

## Geospatial visualiztion on Bay Wheels data
- San Francisco has highest number of bike stations as compared to other cities. San Jose, on the other hand, has the lowest number of bike stations. One of the many factors attributing to this is San Francisco receiving a higher number of tourists in comparison to San Jose who tend to opt for bike sharing facility for traversing through the city.
- Townsend St at 4th St in San Francisco shows the highest density of users. Also, many stations on Market street serve as a starting points for a bike trip. 
- Subscriber uses the bike sharing service much more than a Lyft Customer. It seems Lyft Customer takes some particular routes maybe they are tourists.


Analysis on my [Medium]!

[Medium]:https://sheetalkalburgi.medium.com/
