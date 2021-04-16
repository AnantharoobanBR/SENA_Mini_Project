# SENA_Mini_Project

PROBLEM STATEMENT
Airline network is one of the largest networks in the world spanning entire globe. According to ICAO’s annual global statistics, 4.5 billion people travelled by air in the year 2019. Hence it is vital to manage and analyze the world airline networks to enhance the travel experience and efficiency of the world air transport. Real world flight networks can be modelled as a graph where each node represents an airport and a directed edge between two nodes A to B represent the existence of a direct flight from airport A to B. Here, we analyze a sample data set of Airline networks spanning Canada and USA.

DATASET DESCRIPTION
We have considered a dataset which is a Airline reachability network for cities in Canada and USA. The edges in the dataset are weighted in a way that there is an edge from city i to city j if airline travel time is less than a threshold value. The travel time includes the stopover delays also. The network is asymmetric because of headwinds. Dataset includes the city metropolitan populations, latitude, and longitude.
Attributes of reachability dataset
--from node: source city id 
--to node: destination city id 
--weight: Estimated airline travel time based on a threshold
Attributes of reachability-meta dataset 
--node id: city id or airport id 
--name: city name 
--metro pop : Population of a city 
--latitude : geographical latitude of city 
--longitude : geographical longitude of city
