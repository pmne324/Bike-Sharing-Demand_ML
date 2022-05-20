# Bike-Sharing-Demand_ML
EDA, feature engineering and regression machine learning for 'Bike Sharing Demand' dataset</br>
Machin learning (ML) for 'Bike Sharing Demand' dataset</br>
This notebook contain EDA(Exploratory Data Analysis), Feature Engineering and Machin Learning with regression models.</br>
DataSet for train is available in train.csv, for test is available in test.csv and for submission in sampleSubmission.
## Requirements:
Requirement modules are available in requirements.txt and you can install them with :</br>
<pre>
pip install -r requirements.txt </br>
</pre>
Or you can install requirements with follow commands :</br>
<pre>
pip install jupyter</br>
pip install numpy</br>
pip install pandas</br>
pip install matpoltlib</br>
pip install seaborn</br>
pip install plotnine</br>
pip install pandas-profiling (optional)</br>
</pre>
## DataSet Description :
datetime : hourly date + timestamp</br>
season:</br>
---> 1 = spring</br>
---> 2 = summer</br>
---> 3 = fall</br>
---> 4 = winter</br>
holiday : whether the day is considered a holiday</br>
workingday : whether the day is neither a weekend nor holiday</br>
weather:</br>
---> 1: Clear, Few clouds, Partly cloudy, Partly cloudy</br> 
---> 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist</br>
---> 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds </br>
---> 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog </br>
temp : temperature in Celsius</br>
atemp : "feels like" temperature in Celsius</br>
humidity : relative humidity</br>
windspeed : wind speed</br>
casual : number of non-registered user rentals initiated</br>
registered : number of registered user rentals initiated</br>
count : number of total rentals</br>
