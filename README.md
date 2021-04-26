# python-api-challenge
Python API challenge Databootcamp

# Open Weather API - Part I
In this homework activity we were asked to the following:
1. Utilized citipy module
	In this module we are learnt to use available module to generate nearest city based on the latitude and longitude coordinates that we have provided. Approximately 500+ cities have to be generated. 
2. OpenWeatherMap's API. 
	From no. 1, We then use OpenWeatherMap's API to determine the weather of the location's weather (max temperature, humidity, cloudiness, and wind speed)
3. Analysed our data
	Now that our data is completed. we can start analysing the data. The exercise here to see the relation between each parameters. For instance the relation between latitude coordinate and max temp, and so on. Matplotlib module was used to do the analysis of the data. By data visualization we are able to see the relation or tell story about the data.
In addition, we are also used linear regression to see correlation between the data. Linear regression can also be used to predict the outcome of an event based on the given parameter accurately, depending how close the r-value to 1. Closer to 1 meaning our model is very representative, further away, meaning almost no correlation between the parameters and outcome.
4. Observed obvious trend
	From the analysis above, we are asked to make summary of the observations.
5. Bonus
	As a bonus we are asked to develop a function to create the plot. It is make sense, because on the main task we are asked to generate few plot repeatedly. If we have created function, we can create list of data, then just call the function that we have created in a loop. So program is more efficient and appealing.
 
# Gmaps Heatmap and Marker Plot - Part II
In this homework activity we were asked to the following:
1. Utilize gmaps module
	This homework is continuation of the part I, from the dataframe that we have generated we are asked to create heat map layer using all of the coordinates that we have generated. The layer will be plot on top of world map.
2. Filtering the city 
	In this step we are filtering the city so that we are not exceed the limit of API calls, in addition also to accostume on how filter things with Pandas.
3. Using google geocoding and geoplaces APIs
	After filtering the cities, we are task to find nearest lodging/hotel. However there is a catch, The cities generated on the Part I is actually based on the nearest city so not actual latitude and longitude coordinates of the city. Hence, we need to use Geocoding APIs to find the exact coordinate. If we dont do this, in the following task, we wont be able to find any hotels due to coordinates given maybe in the sea, or outside 5km radius that we set.
	Once the actual cities coordinates are obtained, we need to use geoplaces API to search for the hotel. Once we have done this, a new dataframe is created, which consist of city, country and hotel name in the column.
4. Creating marker and save it as layer
	Next task is to create marker of each hotel on the cities. The marker consist of name of the city, country and hotel name. Once the marker layer is created, we are to visualise on top of the heatmap layer from activity no. 1 on this part II.



