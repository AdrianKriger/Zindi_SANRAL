Predicting Road Accidents

I happened upon the Uber Movement SANRAL Cape Town Challenge on Zindi and decided to have a go. It seemed a great way to practice data wrangling with pandas and geopandas and work at Machine Learning. I'm a novice so the probability that everything I do here is wrong; is very high.

The intention is to have a number of notebooks. We'll start with simple data manipulation and building a Machine Learning model. Then we'll harvest weather data and include that. Car count and travel time will be included as we go along.

We start with Machine Learning; but I'm on the fastai course and I'd like to give their tabular method a try: so the intension is to end with that.
Data

These solutions use the data provided by the Zindi competition. It's local and a wonderful way to create knowledge.

It mentions weather data can be added. I'll use NOAA NCDC Integrated Surface Data; to utilize the skills learnt through the Universtity of Helsinki Geo-Python and Automating GIS-processes courses.
Process:

There will hopefully be two solutions: A xgboost and fastai. We'll build towards the later.

Process:
 
   1) Wrangle data, run a simple model and make predictions;
   2) Harvest and add weather, update predictions;
   3) Harvest car count and repeat;
   4) Include travel time and repeat;
   5) Give fastai a go.
