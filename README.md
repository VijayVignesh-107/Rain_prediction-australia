# Rain_prediction-australia

Hi,

As part of my data science journey, I have taken a dataset that contains daily weather observations from numerous Australian weather stations. The goal is to build a supervised learning model to predict the rain on next day with current climatic conditions of the present day.

This dataset consist of 23 columns which represent each climatic criteria that influence the daily weather.

Link to the dataset: https://www.kaggle.com/code/karnikakapoor/rain-prediction-ann/input

# Dataset description:

Date : This column gives us the date that the climatic conditions have been recorded.

Location : This column gives us the location of the weather station in australia where the climitaic parameters has been recorded.

MinTemp: This column gives us the minimum temperature recorded for that particular date in that weather staion in celcius.

MaxTemp: This column gives us the maximum temperature recorded for that particular date in that weather staion in celcius.

Rainfall: This column gives us the amount of rainfall recorded for the day in mm.

Evaporation: The so-called Class A pan evaporation (mm) in the 24 hours to 9am

Sunshine: The number of hours of bright sunshine in the day.

WindGustDir: The direction of the strongest wind gust in the 24 hours to midnight

WindGustSpeed: The speed (km/h) of the strongest wind gust in the 24 hours to midnight

WindDir9am: Direction of the wind at 9am

WindDir3pm: Direction of the wind at 3pm

WindSpeed9am: Wind speed (km/hr) averaged over 10 minutes prior to 9am

WindSpeed3pm: Wind speed (km/hr) averaged over 10 minutes prior to 3pm

Humidity9am: Humidity (percent) at 9am

Humidity3pm: Humidity (percent) at 3pm

Pressure9am: Atmospheric pressure (hpa) reduced to mean sea level at 9am

Pressure3pm: Atmospheric pressure (hpa) reduced to mean sea level at 3pm

Cloud9am: Fraction of sky obscured by cloud at 9am. This is measured in "oktas", which are a unit of eigths. It records how

Cloud3pm: Fraction of sky obscured by cloud (in "oktas": eighths) at 3pm. See Cload9am for a description of the values

Temp9am: Temperature (degrees C) at 9am

Temp3pm: Temperature (degrees C) at 3pm

RainToday: Boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0

RainTomorrow : The amount of next day rain in mm. Used to create response variable RainTomorrow. A kind of measure of the "risk".

Dependent column vs independent column:
Independent column/variable: The variable that are not affected by the other variables are called independent variables. These variables/column influences on the decision or the outcome of the dependent column. The independent columns in this dataset are (Student_ID, Study_Hours_Per_Day, Extracurricular_Hours_Per_Day, Sleep_Hours_Per_Day, Social_Hours_Per_Day, Physical_Activity_Hours_Per_Day, GPA)

Dependent column/variable: The variable that are affected by the other variables are called dependent variables. These variables/column gets influenced by the decision or the outcome of the independent column. The dependent columns in this dataset are (Stress_Level)
