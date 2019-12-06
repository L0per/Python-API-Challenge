# OpenWeatherMap API
* Testing this api to find relationships between latitude and various weather station data across the world.

## Data
* 10,0000 latitude and longitude coordinates were randomly generated and passed through citypy to find the nearest cities
* Using the openweathermap API, weather data was requested for ~2,300 cities, resulting in weather information for 2,100 cities

## Plots
### Latitude vs. Temperature (F)
* Observations
  * Lack of datapoints below latitude -20
    * Not surprising given the lower population and land mass of the southern hemisphere
  * The plot forms a parabola
    * Expected due to cooler temperatures near the poles
  * Some of the greatest temperatures are found just below latitude -20
    * Major deserts are found around this latitude
    
![Latitude vs Temperature](https://github.com/L0per/Python-API-Challenge/blob/master/City%20Latitude%20vs%20Max%20Temperature.png?raw=true)

### Latitude vs. Humidity (%)
* Observations
  * Humidity is high near the equator and latitudes 50-70
    * Not surprising that the humidity is high near the equator
    * The high humidity around latitudes 50-70 could be due to the large forests in Siberia and western Russia, also large Canadian forests
    
![Latitude vs Humidity](https://github.com/L0per/Python-API-Challenge/blob/master/City%20Latitude%20vs%20Humidity.png?raw=true)

### Latitude vs. Cloudiness (%)
* Observations
  * Low cloudiness in latitudes 20-40
    * These latitudes contain the mediteranian zone, which have very mild weather
    
![Latitude vs Cloudiness](https://github.com/L0per/Python-API-Challenge/blob/master/City%20Latitude%20vs%20Cloudiness.png?raw=true)

### Latitude vs. Wind Speed (mph) 
* Observations
  * Average wind speed increases towards the poles, paticularly the southern pole
    * This is not surprising given the violent storms around the cities closer to the poles (Cape of Good Hope, Cape horn, etc.)
    
![Latitude vs Wind Speed](https://github.com/L0per/Python-API-Challenge/blob/master/City%20Latitude%20vs%20Wind.png?raw=true)
