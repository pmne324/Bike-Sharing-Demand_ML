# Bike-Sharing-Demand_ML
EDA, feature engineering and regression machine learning for 'Bike Sharing Demand' dataset</br>
Machin learning (ML) for 'Bike Sharing Demand' dataset</br>
This notebook contain EDA(Exploratory Data Analysis), Feature Engineering and Machin Learning with regression models.</br>
DataSet for train is available in train.csv, for test is available in test.csv and for submission in sampleSubmission.
## Requirements:
Requirement modules are available in requirements.txt and you can install them with :</br>
$ pip install -r requirements.txt </br>
Or you can install requirements with follow commands :</br>
$ pip install jupyter</br>
$ pip install numpy</br>
$ pip install pandas</br>
$ pip install matpoltlib</br>
$ pip install seaborn</br>
$ pip install plotnine</br>
$ pip install pandas-profiling (optional)</br>

## DataSet Description :
datetime - hourly date + timestamp</br>
season:</br>
&emsp1 = spring</br>
&emsp2 = summer</br>
&emsp3 = fall</br>
&emsp4 = winter</br> 
holiday - whether the day is considered a holiday</br>
workingday - whether the day is neither a weekend nor holiday</br>
weather:</br>
&emsp1: Clear, Few clouds, Partly cloudy, Partly cloudy</br> 
&emsp2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist</br>
&emsp3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds </br>
&emsp4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog </br>
temp - temperature in Celsius</br>
atemp - "feels like" temperature in Celsius</br>
humidity - relative humidity</br>
windspeed - wind speed</br>
casual - number of non-registered user rentals initiated</br>
registered - number of registered user rentals initiated</br>
count - number of total rentals</br>
