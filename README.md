# World_Weather_Analysis
## The University of Texas at Austin Data Visualization and Analytics Bootcamp module 6: Python API's

This module provided me with an introduction to retrieving and analyzing data through APIs, python, and JSON. In this module challenge, I analyzed weather data for a hypothetical travel company app and produced 3 technical analyses.

#### 1: Connected to a weather data website and retrieved global weather information for random cities around the world.
#### 2: Cross-referenced the weather data with Google maps to identify cities and lodgings that met specific temperature inputs collected from a theoretical customer.
#### 3: Produced a map route for 4 potential destinations using data from previous results.


### 1: Retrieve the Weather Data
In the first deliverable, I performed an API call using a set of 2,000 random latitude and longitude pairings. I obtained different types of data about these pairings such as their maximum temperature, the current humidity percentage, and even the current weather description. I then added this data into a new Dataframe using python script. 

### 2: Create a Customer Travel Destinations Map
In the second deliverable, I created a heatmap that showed potential travel locations with nearby hotels. Using input statements, the theoretical customer would type in their desired minimum and maximum temperature. This information would then be used to filter the data frame previously created, then used to create a map of those vacation destinations and local hotels. 

### Create a Travel Itinerary Map
In the final deliverable, I chose four possible cities from the filtered data frame that was based on the customer's preferred temperature. Using Google Directions API, I created a map that showed the route that passed through all four of these cities by way of bicycling. This map was similar to the previous deliverable's map with the pop-up markers for each of the cities. 
