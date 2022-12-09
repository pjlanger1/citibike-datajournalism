CONTENTS OF PRODUCTION CODE DIRECTORY:
Mapping Tables which are useable for ETL Processes on this project:

I. citibike_m_station_prox_ct.csv - a file with station-wise counts of bike lane segments within 0.5, 0.25, and 0.10 miles of their coordinates


II. central_park_adj_station_distances.csv - a file with distance from central park for all stations within half a mile of the park, as well as discretized distance from park.


III. manhattan_distances_trip_directions.csv.zip - the master file with all unique trip distances, directions.
**distance_miles** is crow distance between stations
**direction_n_pole** are the cardinal directions of the trip, divided across an eight directional 360 degree compass.
**direction_ny** contains direction of travel relative to NY (using degree of bearing minus 29 degrees), UP is uptown, DOWN is downtown, cross-town directions also mapped.

start_station_id	end_station_id	distance_miles	start_lat	end_lat	start_lng	end_lng	dir	dir_rect_pole	dir_rect_ny	direction_n_pole	direction_ny
