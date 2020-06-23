Predicting Road Accidents   
==========================

I happened upon the Uber Movement SANRAL Cape Town Challenge on [Zindi](https://zindi.africa/competitions/uber-movement-sanral-cape-town-challenge) and decided to have a go. It seemed a great way to practice data wrangling with ```pandas``` and ```geopandas``` and work at Machine Learning. I'm a novice so the probability that everything I do here is wrong; is very high. 

The idea is to have a number of ```notebooks```. We'll start with simple data manipulation and building a Machine Learning ```model```. Then we'll harvest weather data and include that. Car count and travel time will be included as we go along. 

We start with Machine Learning; but I'm on the [fastai](https://course.fast.ai/) course and I'd like to give their ```tabular``` method a try: so the intension is to end with that.  

Anticipating an increase in file size, and the inability of a laptop to process massive ```csv``` files, I'll run the entire process through [Colab](https://colab.research.google.com/notebooks/intro.ipynb); with files on [Google Drive](https://www.google.com/drive/). The 12GB of of free ```RAM``` should be enough - best practice suggest only using it when neccessary and terminating the session before exit. ```code``` to load GDrive as a filesystem are in the ```notebooks```.

### Data

These solutions use the data provided by the [Zindi competition](https://zindi.africa/competitions/uber-movement-sanral-cape-town-challenge/data). It's local (City of Cape Town, South Africa) and a wonderful way to create knowledge.
 
It mentions weather data can be added. I'll use [NOAA NCDC Integrated Surface Data](https://www.ncdc.noaa.gov/isd); to utilize the skills learnt through the [Universtity of Helsinki](https://www.helsinki.fi/en) [Geo-Python](https://geo-python.github.io/site/) and [Automating GIS-processes](https://automating-gis-processes.github.io/site/) courses. 
   
### Process:

There will hopefully be two solutions: A [xgboost](https://xgboost.readthedocs.io/en/latest/) and [fastai](https://www.fast.ai/). We'll build towards the later. 

    Process:

       1) Wrangle data, run a simple model and make predictions;
       2) Harvest and add weather, update predictions;
       3) Harvest car count and repeat;
       4) Include travel time and repeat;
       5) Give fastai a go.
