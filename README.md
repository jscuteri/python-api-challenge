# Python API – Weather and Vacation 

# Background

Using Python, Google APIs, and JSON, prove that the weather gets hotter as you approach the equator. Additionally, find various vacation spots and layer them on a map.

# Part I – Weather Analysis

Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 

Created a series of scatter plots to showcase the following relationships. Additionally, add a sentence or two explaining what the code is analyzing

•	Temperature (F) vs. Latitude

•	Humidity (%) vs. Latitude

•	Cloudiness (%) vs. Latitude

•	Wind Speed (mph) vs. Latitude

 ![image](https://user-images.githubusercontent.com/87212158/148706503-1590b580-ccc3-416c-9422-c992fb548e15.png)

Ran linear regression on each relationship using the variables above but separating it by hemisphere. Additionally, add a sentence or two explaining what the code is analyzing

•	Northern Hemisphere - Temperature (F) vs. Latitude

•	Southern Hemisphere - Temperature (F) vs. Latitude

•	Northern Hemisphere - Humidity (%) vs. Latitude

•	Southern Hemisphere - Humidity (%) vs. Latitude

•	Northern Hemisphere - Cloudiness (%) vs. Latitude

•	Southern Hemisphere - Cloudiness (%) vs. Latitude

•	Northern Hemisphere - Wind Speed (mph) vs. Latitude

•	Southern Hemisphere - Wind Speed (mph) vs. Latitude

![image](https://user-images.githubusercontent.com/87212158/148706513-02bac58b-f352-4c64-9bb1-154c3b55306d.png)

# Part II – Vacation Analysis

Using the weather data compiled above, I utilized the Google Places API to find optimal vacation spots. 

•	The filters I put in place for an optimal vacation were:

o	A max temperature lower than 80 degrees but higher than 70.

o	Wind speed less than 10 mph.

o	Zero cloudiness.

o	Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.

![image](https://user-images.githubusercontent.com/87212158/148706525-cf4bc738-dc22-47c4-acb1-8f7dc432b01c.png)

•	I then found the first hotel for each city located within 5000 meters of the coordinates and placed a pin containing the Hotel Name, City, and Country.
 
![image](https://user-images.githubusercontent.com/87212158/148706534-c4e5509c-f4cb-4164-ac97-58e5c7dd688a.png)

