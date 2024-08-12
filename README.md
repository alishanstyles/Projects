# Fremont-Bridge-Bicycle-Counter
## Problem Statment  
- The Fremont Bridge Bicycle Counter began operation in October 2012 and records the number of bikes that cross the bridge using the pedestrian/bicycle pathways. Inductive loops on the east and west pathways count the passing of bicycles regardless of travel direction. The data consists of a date/time field: Date, east pathway count field: Fremont Bridge NB, and west pathway count field: Fremont Bridge SB. The count fields represent the total bicycles detected during the specified one hour period. Direction of travel is not specified, but in general most traffic in the Fremont Bridge NB field is travelling northbound and most traffic in the Fremont Bridge SB field is travelling southbound. The is data set set is from the [Seattle Transportation Website](https://data.seattle.gov/Transportation/Fremont-Bridge-Bicycle-Counter/65db-xm6k/about_data) There are 4 columns and 102947 rows. 

## Dictionary 
Column Name                                                        | Description                                                                                          | API Field Name    | Data Type
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Date                                                               | The date and hour of day object(s) are detected by the sensor.                                       | date              | Floating Timestamp
Fremont Bridge Sidewalks, south of N 34th St                       | Total of both sidewalks                                                                              | fremont_bridge    | Number
Fremont Bridge Sidewalks, south of N 34th St Cyclist West Sidewalk | The total number of bicyclists traveling on the West sidewalk in one hour as recorded by the sensor. | fremont_bridge_nb | Number
Fremont Bridge Sidewalks, south of N 34th St Cyclist East Sidewalk | The total number of bicyclists traveling on the East sidewalk in one hour as recorded by the sensor. | fremont_bridge_sb | Number

