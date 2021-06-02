# python-api-challenge
Python API homework

We were tasked with using API calls to randomly locate 500+ unique cities and the following attributes:

Latitudes/Longitudes
Temperatures
Humidities
Cloudiness
Wind Speeds

Once the above factors were discovered through creating a nested loop, a dataframe was created as a placeholder. API calls were made for each unique city in our list. A sample city (London) was used to see how the list was formed through the json reponse (as a list). This allowed us to pinpoint our latitude, longitude, temp, humidity, cloudiness, and wind speed for all 700 cities and plot the results in a scatter plot.


3 observations:
Locations that are further away from the equator have the highest wind speed than those 
closer to the equator or with warmer climates.

Cities with a latitudes that are close to 0° have warmer temperatures since this is near the equator.

Cloudiness and the distance a city is from the equator has no relation, and because of this, I was unable to find consistency. Cities with a latitude of 45° had the least amount of cloudiness.