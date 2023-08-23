# python-api-challenge

The deliverable for this repository was to create a Python script to visualize the weather of over 500 cities of varying distances from the equator. Using the OpenWeather API and the Started Code provided, a list of random geographic coordinates and cities were populated in a dataframe. Using lat/long, weather measures were pulled into a list and used to visualize correlations to one another. Scatter plots were used to show City Latitude vs. Temperature:


![output_data_Fig1](https://github.com/stephmgutierrez/python-api-challenge/assets/127039290/1cdfac8d-fc29-4069-906e-869606c9109d)

Latitude vs Humidity:

![output_data_Fig2](https://github.com/stephmgutierrez/python-api-challenge/assets/127039290/116c75a1-844c-4b33-8009-60babfa217ae)

Latitude vs Cloudiness:

![output_data_Fig3](https://github.com/stephmgutierrez/python-api-challenge/assets/127039290/204854fc-829e-4726-850f-deaee3a7f156)


Latitude vs Wind Speed:

![output_data_Fig4](https://github.com/stephmgutierrez/python-api-challenge/assets/127039290/50f8a7b1-95aa-4b28-9c86-68eda02038ab)

We also used the Linear Regression which only showed real value when comparing Temperature vs Latitude; in conclusion the closer you get to the equator, the more the temperature rises.

The same data was also used to plot hotels on on a map and use dot size to signify humidity:

![image](https://github.com/stephmgutierrez/python-api-challenge/assets/127039290/b43b890a-c640-4e00-b95d-071df3ffd4fb)
