# Readme

weatherStations.zip file contains several CSVs.
Each CSV file has 4 columns: 
day | percipitations | min_temperature | max_temperature
Dataset1 and Dataset2 are the dataset folders used to train our LSTM model.

weather-stations-position.json contains the list of the coordinates of all the weather stations used. 

areas-of-interest.geojson contains a geojson feature collection representing the area of interest in which the fields have been selected. The area is partitioned into polygons and the terrain selection has been done in order to balance the samples within these polygons.
