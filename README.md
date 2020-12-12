# bike-share-demand

![The Bike Sharing Demand Prediction Task](https://user-images.githubusercontent.com/14073798/101976631-985eef80-3c79-11eb-9810-f570cec7df76.png)


The goal of this task is to predict bike demands for the last 2 weeks of each month given the first 2 weeks bike demands data (constant horizontal lines on the plot above). 
These are all of the features obtained in the dataset :
- datetime (yyyy-mm-dd hh-mm-ss)
- season (1 = spring, 2 = summer, 3 = fall, 4 = winter)
- holiday (0 = non holiday, 1 = holiday)
- weekday (0 = Mon, ... 6 = Sunday)
- workingday (0 = non working day, 1 = working day)
- weather (1 = Clear, Few clouds, Partly cloudy, Partly cloudy; 
           2 =  Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist; 
           3 = Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds; 
           4 = Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog ])
- temp (transformed actual temperature)
- atemp (transformed 'feels like' tempetarure)
- humidity (%)
- windspeed (transformed windspeed)
- casual (number of non-registered user rentals initiated)
- registered (number of registered user rentals initiated)
- cnt (total rents)
