first ,download data from http://comet.nefsc.noaa.gov:8080/erddap/tabledap/drifters.html and save it,which name is drifters.csv

second,create a file which name is data

third,run segment.py, according to drifter's is and time,we divide it into different segments and save the file of 'data'

forth,run drifter_vs_model_use_hourly_data.py and calculate separation rate and distance ratio

finally,run draw.py and draw density map
