# Bike_Rental_Service

BACKGROUND AND PROBLEM STATEMENT
Bike sharing systems are a new generation of traditional bike rentals where the whole process from membership, rental and return has become automatic. Through these systems, users are able to easily rent a bike from a particular position and return back at another position. Currently, there are about over 500 bike-sharing programs around the world which is composed of over 500 thousand bicycles. Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues.
One of our leading automobile clients having bike rental service wants to predict the number of the bikes demand on the hour basis using machine learning regression technique which increases the productivity and cost effectiveness, and able to manage the operations more efficiently. With these analysis they'll be able to track demand, supplies, managements, maintenance which can be utilized to work on strategy building part to compete with their market competitors.

DATASET DESCRIPTION
instant: record index
date : date of the record
=season_type : season (1:winter, 2:spring, 3:summer, 4:fall)
=year : year (0: 2011, 1:2012) of the record
=month : month ( 1 to 12) of the record
hour : hour (0 to 23) of the particular recorded date
=holiday_or_not : weather day is holiday or not (extracted from [Web Link])
=week_day : day of the week
=working_day : if day is neither weekend nor holiday is 1, otherwise is 0.
=weather_sit : 1: Clear, Few clouds, Partly cloudy, Partly cloudy 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
temperature : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
atemperature: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
humidity: Normalized humidity. The values are divided to 100 (max)
windspeed: Normalized wind speed. The values are divided to 67 (max)
casua_user: count of casual users
registered_user: count of registered users
count: count of total rental bikes including both casual and registered
