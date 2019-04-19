# DS_Mod_2_Project
Predicting Tips for NYC yellow cab rides using data provided by the Taxi & Limousine Commission as well as weather data pulled from the Dark Sky API.

## Methodology ##
* Pulled October 2018 data from Dark Sky API and NYC TLC Trip Record Data
* Dependent variable: tip amounts (in USD)
* Indepdent variables tested: trip distance, fare amount, toll amount, trip time, temperature, inclimate weather, passenger count, rate code (i.e. standard fare or trip from airport), payment, day of week, time of day, neighborhoods and boroughs.

## Challenges ##
* Large data set: almost 9 million records with an initial sample of 250,000 later reduced to 50,000
  * Caused certain algorithms to take a long time to run
* Tips were not normally distributed
![chart1](Charts/tip_amount_dist.png)<br>
