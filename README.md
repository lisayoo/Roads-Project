# Roads-Project

### Purpose
To evaluate the efficiency of a road network in downtown Ithaca, NY and to propose a new location for a bus stop such that traffic congestion is alleviated

### Methodology Overview
Based on what we had learned about topological data analysis and how PageRank works, we decided to take a local road network to be a graph, with intersections as nodes and streets as edges. We collected relevant data on any factors that could affect cars and pedestrians, including number of lanes, directionality, bus stops, nearby points of interest, and more. We created formulas to model the traffic, giving weight to the edges, and computed two PageRanks -- one for car traffic, and another for pedestrian traffic.

We assumed that the best location for a new bus stop would be a node that would be located where pedestrian traffic was heavy, but car traffic was light. Examining the PageRanks, we were able to locate the node that maximized this difference in weights, where a bus stop did not already exist. 
