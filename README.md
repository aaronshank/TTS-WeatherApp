# TTS-WeatherApp

In Class project.

Activity is fully working now. Feel free to compare code to see where your errors are.

Application.properties is .gitignore'd but it only has the api_key in it.

# Homework :
Modify the app so that it displays a list of the 10 most recent searches. Here is a summary of the changes you'll need to make: (*Note*: **Bolded** is completed)
* **Add the necessary database settings to application.properties.**
* **Create a model/entity to store zip codes in the database.**
* **Create a zip code repository.**
* Inject the zip code repository into the weather service.
* Any time the getForecast method is called in the weather service, add the zip code to the database.
* Create a weather service method to get the (up to 10) most recent searches.
* In both of the weather controller methods, call the new service method and add the the list of zip codes to the model.
* In both of the weather controller methods, call the new service method and add the the list of zip codes to the model.
* In the html page, add code to display the recent searches in a table.

Use the weather description in the API response to dynamically change the background on the page. You will have to get images from unsplash.com for each possible weather scenario.