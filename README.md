# Prediction-of-Forest-Fires-in-Northern-Portugal

## Background
I chose to use a dataset that studies the size of forest fires based on a variety of predictors from UCI’s machine learning repository (data was collected in Northern Portugal).

My goal is to build data analysis models to determine predictors in the dataset that could be used to predict how large a forest fire will be. The response variable is the area measured in hectares (ha: 1 ha = 10,000 meters^2) a fire was able to burn before being put out.

This anlaysis is useful because if firefighters can predict how large a fire will be, they can adequately prepare to fight it. For example, if a fire is predicted to be small, they can send fewer resources to fight it than they would have otherwise. This is especially useful during the fire season, when the fire department has to fight multiple fires simultaneously.

Analysis on this dataset can also give some clues as to some causes of fires. This could be useful in predicting where and when fires will occur.

Variables: "1. X - x-axis spatial coordinate within the Montesinho park map: 1 to 9

Y - y-axis spatial coordinate within the Montesinho park map: 2 to 9
month - month of the year: 'jan' to 'dec'
day - day of the week: 'mon' to 'sun'
FFMC - FFMC index from the FWI system: 18.7 to 96.20
DMC - DMC index from the FWI system: 1.1 to 291.3
DC - DC index from the FWI system: 7.9 to 860.6
ISI - ISI index from the FWI system: 0.0 to 56.10
temp - temperature in Celsius degrees: 2.2 to 33.30
RH - relative humidity in %: 15.0 to 100
wind - wind speed in km/h: 0.40 to 9.40
rain - outside rain in mm/m2 : 0.0 to 6.4
area - the burned area of the forest (in ha): 0.00 to 1090.84 (this output variable is very skewed towards 0.0, thus it may make sense to model with the logarithm transform)."
Reference for dataset and variable descriptions: https://archive.ics.uci.edu/ml/datasets/forest+fires

Reference for study that dataset was originally used for: http://www3.dsi.uminho.pt/pcortez/fires.pdf

Reference: https://en.wikipedia.org/wiki/Hectare
