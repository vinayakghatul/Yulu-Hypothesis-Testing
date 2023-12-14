# Yulu-Hypothesis-Testing

### About Yulu

Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.

Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!

Yulu has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.

### Problem Statement

The company wants to know:

Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
How well those variables describe the electric cycle demands.


### Dataset:

Dataset Link: yulu_data.csv

### Column Profiling:

datetime: datetime
season: season (1: spring, 2: summer, 3: fall, 4: winter)<br>
holiday: whether day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)<br>
workingday: if day is neither weekend nor holiday is 1, otherwise is 0.<br>
weather:<br>
1: Clear, Few clouds, partly cloudy, partly cloudy<br>
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist<br>
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds<br>
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog<br>
temp: temperature in Celsius<br>
atemp: feeling temperature in Celsius<br>
humidity: humidity<br>
windspeed: wind speed<br>
casual: count of casual users<br>
registered: count of registered users<br>
count: count of total rental bikes including both casual and registered<br>

### Concept Used:

Bi-Variate Analysis<br>
2-sample t-test: testing for difference across populations<br>
ANNOVA<br>
Chi-square<br>

