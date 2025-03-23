# Bus lanes
Travel time savings if fleets are allowed to use dedicated bus lanes



This project analyzes vehicle trip data to estimate potential time savings if fleet vehicles are allowed to use bus lanes. The analysis is based on GPS coordinates of vehicle trips and geographical information about designated bus lanes.



trips.csv — vehicle trip data 
bus_lanes.geojson — data on designated bus lanes containing route geometries (LineString).


How It Works:
Loads vehicle trip data and bus lane data.
Creates vehicle movement trajectories (LineString).
Checks which route segments pass within 30 m of designated bus lanes.
Calculates the average vehicle speed and compares it with the expected speed on bus lanes.
Estimates potential time savings for trips.


Expected Results:
Total time savings (in hours) when using bus lanes..

