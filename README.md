# Road-Accident-Severity-Prediction
In recent years, Road Accidents (RAs) have emerged as an important public health issue which needs to be tackled by a multi-disciplinary approach. The trend in RA injuries and death is becoming alarming. A road traffic accident can be defined as, an event that occurs on a way or street open to public traffic resulting in one or more persons being injured or killed, where at least one moving vehicle is involved. The important factors are human errors, driver fatigue, poor traffic sense, mechanical fault of vehicle, speeding and overtaking violation of traffic rules, poor road conditions, traffic congestion, road encroachment etc. 

This analytical project will analyze traffic accidents more deeply to determine the intensity of accidents by using machine learning approaches. It also figures out those significant factors that have a clear effect on road accidents and provide some beneficent suggestions regarding this issue. 

In this project, we will be using classification methods to predict the severity of the road accidents.

Description:

This is a countrywide car accident dataset, which covers 49 states of the USA. The accident data are collected from February 2016 to Dec 2020, using two APIs that provide streaming traffic incident (or event) data. These APIs broadcast traffic data captured by a variety of entities, such as the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road-networks. Currently, there are about 4.2 million accident records in this dataset

Content:

This dataset has been collected in real-time, using multiple Traffic APIs. Currently, it contains accident data that are collected from February 2016 to Dec 2020 for the Contiguous United States.

Parameters Explanations:

ID: This is a unique identifier of the accident record.
Source: Indicates source of the accident report (i.e. the API which reported the accident.)
TMC: A traffic accident may have a Traffic Message Channel (TMC) code which provides more detailed description of the event.
Severity: Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic (i.e., short delay as a result of the accident) and 4 indicates a significant impact on traffic (i.e., long delay).
Start_Time: Shows start time of the accident in local time zone.
End_Time: Shows end time of the accident in local time zone. End time here refers to when the impact of accident on traffic flow was dismissed.
Start_Lat: Shows latitude in GPS coordinate of the start point.
Start_Lng: Shows longitude in GPS coordinate of the start point.
End_Lat: Shows latitude in GPS coordinate of the end point.
End_Lng: Shows longitude in GPS coordinate of the end point.
Distance(mi): The length of the road extent affected by the accident.
Description: Shows natural language description of the accident.
Number: Shows the street number in address field.
Street: Shows the street name in address field.
Side: Shows the relative side of the street (Right/Left) in address field.
City: Shows the city in address field.
County: Shows the county in address field.
State: Shows the state in address field.
Zipcode: Shows the zipcode in address field.
Country: Shows the country in address field.
Timezone: Shows timezone based on the location of the accident (eastern, central, etc.).
Airport_Code: Denotes an airport-based weather station which is the closest one to location of the accident.
Weather_Timestamp: Shows the time-stamp of weather observation record (in local time).
Temperature(F): Shows the temperature (in Fahrenheit).
Wind_Chill(F): Shows the wind chill (in Fahrenheit).
Humidity(%): Shows the humidity (in percentage).
Pressure(in): Shows the air pressure (in inches).
Visibility(mi): Shows visibility (in miles).
Wind_Direction: Shows wind direction.
Wind_Speed(mph): Shows wind speed (in miles per hour).
Precipitation(in): Shows precipitation amount in inches, if there is any.
Weather_Condition: Shows the weather condition (rain, snow, thunderstorm, fog, etc.)
Amenity: A POI annotation which indicates presence of amenity in a nearby location.
Bump: A POI annotation which indicates presence of speed bump or hump in a nearby location.
Crossing: A POI annotation which indicates presence of crossing in a nearby location.
Give_Way: A POI annotation which indicates presence of give_way in a nearby location.
Junction: A POI annotation which indicates presence of junction in a nearby location.
No_Exit: A POI annotation which indicates presence of no_exit in a nearby location.
Railway: A POI annotation which indicates presence of railway in a nearby location.
Roundabout: A POI annotation which indicates presence of roundabout in a nearby location.
Station: A POI annotation which indicates presence of station in a nearby location.
Stop: A POI annotation which indicates presence of stop in a nearby location.
Traffic_Calming: A POI annotation which indicates presence of traffic_calming in a nearby location.
Traffic_Signal: A POI annotation which indicates presence of traffic_signal in a nearby location.
Turning_Loop: A POI annotation which indicates presence of turning_loop in a nearby location.
Sunrise_Sunse: Shows the period of day (i.e. day or night) based on sunrise/sunset.
Civil_Twilight: Shows the period of day (i.e. day or night) based on civil twilight.
Nautical_Twilight: Shows the period of day (i.e. day or night) based on nautical twilight.
Astronomical_Twilight: Shows the period of day (i.e. day or night) based on astronomical twilight.
