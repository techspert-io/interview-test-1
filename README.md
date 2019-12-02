# Full stack developer - angular weather app
You are not timed and can take as long as you wish to complete this task. You'll be creating a new angular project, using a third party API to fetch weather data, and then building an interface to allow for interaction with that data. Finally you'll add some unit tests.

1. Create a new publicly accessible repo for this project. 
2. Create a new angular project with the features specified in this document
3. Submit your branch/repo for review

# Instructions
1. Create a new angular project
2. Use the open weather API to retrieve weather information on at least 10 cities
3. Populate a table within the app with this data
4. Introduce configurable pagination (rows of 5, 10, 20)
5. Introduce sortable columns
6. Introduce a filter for searching by city name
7. Create a graph that displays the temperature for all cities.
8. Include the the mean temperature of all cities on the graph
7. Implement a unit test to confirm the pagination works
8. Implement a unit test for the city filter

# Open weather API

This project makes use of the open weather API for current weather conditions.

> The API key to use for this project is: **194333f5b09188fbda8c4a3bbfea30b2**
> See https://openweathermap.org/current for documentation on the API

If you return weather data on multiple cities, each city should contain the following data: 

```
[  
	{  
		"id":2210221,  
		"name":"Tarhuna",  
		"coord":{  
			"lon":13.6332,  
			"lat":32.43502  
		},  
		"main":{  
		"temp":17,  
		"pressure":1024,  
		"humidity":55,  
		"temp_min":17,  
		"temp_max":17  
	},  
		"dt":1485784982,  
		"wind":{  
		"speed":3.6,  
		"deg":10  
	},  
		"clouds":{  
			"all":40  
		},  
		"weather":[  
			{  
				"id":802,  
				"main":"Clouds",  
				"description":"scattered clouds",  
				"icon":"03d"  
			}  
		]  
	},  
] 
```
