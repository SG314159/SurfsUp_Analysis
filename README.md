# SurfsUp_Analysis
Challenge 9 for UT Bootcamp - SQLite, SQLAlchemy, and Flask

# Overview of Analysis 

### Project Purpose for UT Bootcamp
For this module, we explored SQLAlchemy, SQLite, and Flask. The scenario was researching weather data for a fictious surf & ice cream shop to be located in Hawaii. Our first goal was to use a SQLite file that held the weather data and write code to query the data and answer questions. The second goal was to use Flask within Python for displaying the results of the query using a web browser instead of within Jupyter Notebook as in previous modules.

### Analysis overview
The last question from a possible investor in our surf shop is about the viability of the shop for year-round business. To investigate this, we will look at temperature data for both June and December. The differences between these months will help us determine whether or not the business is sustainable year-round.


# Results
The tables show the results for all June temperatures and December temperatures for the dates in the dataset.
![June And December temperatures](https://github.com/SG314159/SurfsUp_Analysis/blob/main/JuneAndDecember.PNG)

Major points to note from these results are:
1. The mean temperatures are close together, 74.9 degrees vs. 71.04 degrees, and the standard deviations are also similar. Thus although it is slightly cooler on average in December, with slightly higher variation in temperature as well, the two months have very similar temperatures.
2. The maximum temperature for June was 85 and for December was 83. Thus it does get warm enough both months to support surfing and ice cream.
3. The minimum temperature for June was 64 and for December was 56. These cooler temperatures might affect ice cream sales but will probably not affect surfing supply sales as much.


# Summary
The data from June and December show that there is good support from the weather data for sustainability of the surf & ice cream shop. Additional queries that may be helpful would be related to wind and to precipitation. According to a brief internet research the direction and strength of wind can be a major factor in determining the quality of the waves in the ocean. So queries involving the direction and windspeed would be helpful. Rain may affect surfing less, but it will likely influence ice cream sales. In addition to weather data, significant research should be made for existing competition in the area, such as other surf shops and/or ice cream shops. 

