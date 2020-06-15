# Sitting-in-Traffic-is-Terrible.-Is-there-anyway-to-avoid-it-
The goal of our research project is to determine the hotspots for accidents and traffic. We hope to use a clustering classifier to determine the causes and severities of accidents. The dataset is [US Accidents from kaggle.](https://www.kaggle.com/sobhanmoosavi/us-accidents)  
## Data Summary  
ID - This is a unique identifier of the accident record.  
Source - Indicates source of the accident report (i.e. the API which reported the accident.).  
TMCA traffic accident may have a Traffic Message Channel (TMC) code which provides more detailed description of the event.  
SeverityShows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic (i.e., short delay as a result of the accident) and 4 indicates a significant impact on traffic (i.e., long delay).  
Start_TimeShows start time of the accident in local time zone.  
End_TimeShows end time of the accident in local time zone.  
Start_LatShows latitude in GPS coordinate of the start point.  
Start_LngShows longitude in GPS coordinate of the start point.  
End_LatShows latitude in GPS coordinate of the end point.  
End_LngShows longitude in GPS coordinate of the end point.  
Distance(mi)The length of the road extent affected by the accident.  
DescriptionShows natural language description of the accident.  
NumberShows the street number in address field.  
StreetShows the street name in address field.  
SideShows the relative side of the street (Right/Left) in address field.  
CityShows the city in address field.  
CountyShows the county in address field.  
StateShows the state in address field.  
ZipcodeShows the zipcode in address field.  
CountryShows the country in address field.  
TimezoneShows timezone based on the location of the accident (eastern, central, etc.).  
Airport_CodeDenotes an airport-based weather station which is the closest one to location of the accident.  
Weather_TimestampShows the time-stamp of weather observation record (in local time).  
Temperature(F)Shows the temperature (in Fahrenheit).  
Wind_Chill(F)Shows the wind chill (in Fahrenheit).  
Humidity(%)Shows the humidity (in percentage).  
Pressure(in)Shows the air pressure (in inches).  
Visibility(mi)Shows visibility (in miles).  
Wind_DirectionShows wind direction.  
Wind_Speed(mph)Shows wind speed (in miles per hour).  
Precipitation(in)Shows precipitation amount in inches, if there is any.  
Weather_ConditionShows the weather condition (rain, snow, thunderstorm, fog, etc.).  
AmenityA Point-Of-Interest (POI) annotation which indicates presence of amenity in a nearby location.  
BumpA POI annotation which indicates presence of speed bump or hump in a nearby location.  
CrossingA POI annotation which indicates presence of crossing in a nearby location.  
Give_WayA POI annotation which indicates presence of give_way sign in a nearby location.  
JunctionA POI annotation which indicates presence of junction in a nearby location.  
No_ExitA POI annotation which indicates presence of no_exit sign in a nearby location.  
RailwayA POI annotation which indicates presence of railway in a nearby location.  
RoundaboutA POI annotation which indicates presence of roundabout in a nearby location.  
StationA POI annotation which indicates presence of station (bus, train, etc.) in a nearby location.  
StopA POI annotation which indicates presence of stop sign in a nearby location.  
Traffic_CalmingA POI annotation which indicates presence of traffic_calming means in a nearby location.  
Traffic_SignalA POI annotation which indicates presence of traffic_signal in a nearby location.  
Turning_LoopA POI annotation which indicates presence of turning_loop in a nearby location.  
Sunrise_SunsetShows the period of day (i.e. day or night) based on sunrise/sunset.  
Civil_TwilightShows the period of day (i.e. day or night) based on civil twilight.  
Nautical_TwilightShows the period of day (i.e. day or night) based on nautical twilight.  
Astronomical_TwilightShows the period of day (i.e. day or night) based on astronomical twilight.  
## Authors
the list of [contributors](https://github.com/rtora/135_Project/contributors) who participated in this project.
## Acknowledgments  
Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. [“A Countrywide Traffic Accident Dataset.”](https://arxiv.org/abs/1906.05409), 2019.  
Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. ["Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights."](https://arxiv.org/abs/1909.09638) In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.  

