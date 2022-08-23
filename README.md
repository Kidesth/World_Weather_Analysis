# World_Weather_Analysis
### Overview of the Project:
The purpose of this analysis is to use a real-time layered heatmap, users can easily plan their trip according to the weather across the world. Collect and analyze weather data across cities worldwide taking input from the client's weather preferences, Plan My Trip may also give recommendations of ideal hotels in the target city. For designated cities, Plan My Trip can provide appropriate travel routes for their clients.

### Results:

#### Deliverable 1: Retrieve Weather Data
- We were generating a set of 2,000 random latitudes and longitudes, retrieving the nearest city, and performing an API call with the OpenWeatherMap.
Exported csv file


![weather_Database csv d1](https://user-images.githubusercontent.com/107454933/186076400-7f4f1c95-9eb9-4706-b0f5-4ce2036db76e.png)

##### Deliverable 2: Create a Customer Travel Destinations Map
- Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

![WeatherPy_vacation csv exported](https://user-images.githubusercontent.com/107454933/186077807-8fac8231-2ae8-41a5-a91c-b8af8b84881f.png)
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/107454933/186077903-c9169fa0-17d2-453d-8f61-cb5e63f13c28.png)

Deliverable 3: Create a Travel Itinerary Map
- Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then,  create a marker layer map with a pop-up marker for each city on the itinerary.

![delivarable 3 selection vacation  city](https://user-images.githubusercontent.com/107454933/186078676-7cf46f80-9603-4ac2-b58b-7864c78ad406.png)
![WeatherPy_travel_map](https://user-images.githubusercontent.com/107454933/186078807-d1dcbb96-0fd1-46bf-a4a3-7fb614aa54ab.png)
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/107454933/186078822-7f1d9c39-42e5-45ea-983e-d794f2bd9c6f.png)



