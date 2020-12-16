## Welcome to Jarvis v2.0 Github page.

This is the official website of my project [Jarvis v2.0.](https://github.com/JoelShine/Jarvis-v2.0) This project is about my interest in python programming and making my very own virtual assistant. I am a huge fan of Iron Man, not about his suit, but about his virtual assistant, Jarvis. I have uploaded the whole code in my Github repository and it has been a great success !

## About Jarvis v2.0

[Jarvis v2.0](https://github.com/JoelShine/Jarvis-v2.0) is a virtual assistant project. It is made in python and have possibly included a wide range of modules and hope, it will be good in making this project more effective. Some of the use of modules is given below.

### How to find Weather using Jarvis v2.0
All instructions are given in my github project page. Please look it. A sample code is below :

```py
import requests, json

# Enter your API key here
api_key = "Your api key"

# base_url variable to store url
base_url = "http://api.openweathermap.org/data/2.5/weather?"

speak("Sir please give the city name")
city_name = takeCommand()

complete_url = base_url + "appid=" + api_key + "&q=" + city_name

# get method of requests module
# return response object
response = requests.get(complete_url)

# json method of response object
# convert json format data into
# python format data
x = response.json()

if x["cod"] != "404":

y = x["main"]

current_temperature = y["temp"]

current_pressure = y["pressure"]

current_humidiy = y["humidity"]

z = x["weather"]

weather_description = z[0]["description"]
celsius = current_temperature-273.15

speak("Sir, Temperature in " + city_name + "is" + str(celsius) + " degree celsius")
print("Temperature in Celsius = " + str(celsius) + " degree celsius")
print("Temperature in Farenheit = " + str(celsius*9/5+32) + " degree farenheit")

speak("The weather description is " + str(weather_description))
print("Atmospheric pressure = " + str(current_pressure) + " mb")
print("Humidity = " + str(current_humidiy) + " %")
print("Description = " + str(weather_description))
print("")
```
This code will only work if you are running the code in Jarvis v2.0. Because **speak("Something here")** is different for different people.

For more details see .

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/JoelShine/Jarvis-v2.0/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Jarvis v2.0 Github Pages? Check out my Project here at [Jarvis v2.0](https://github.com/JoelShine/Jarvis-v2.0). If you are having any doubt, please comment in my discussions or feel free to open an issue. 
