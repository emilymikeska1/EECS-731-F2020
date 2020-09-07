# EECS-731-F2020

Project1

Industry: Public Services (Police calls)

Datasets: 
1. 2016 calls for service (by quarter, so 4 csv files): Case number, Date Reported, Time Reported, Month Reported, Day of the Week Reported, Nature of Call for Service, District, Agency, Report/No Report
2. Crash data for Bloomington, IN from 2013-2018: Agency, City, Date, Time, VEH#, Trailers, IMJ, Dead, deer, House#, Roadway ID, Intersect Rd., Ramp, Property Type, Feet from, Dir, Latitude, Longitude, Road class, H&R, Locality, School, Rumble Strips, CN Zone, CN Type, Light, Weather, Surf Con, Median, Rd Junction, Road Char, Surface, Primary Factor, Collision Type, Unique Id, Traffic Control

Pre-processing I performed on the data:
•	Load csv files
•	Combine by year
•	Drop superfluous columns
•	Change date and time columns from type ‘object’ to ‘datetime’
•	Fill any empty cells with ‘0’
•	Convert ‘object’ and ‘string’ type columns to ‘category’ types

Ideas on how the datasets could be combined to establish additional values using exploratory data analysis:
•	Percentage of calls from a crash 
•	Density of crashes by location
•	Most likely time of data to crash
•	Most likely weather conditions to crash 
•	Frequency of crashes caused by deer in different months of the year
•	Lethality rates of crashes with various causes
•	Machine learning to determine what environmental factors carry the most weight in the lethality of a crash 
