## Finding Heavy Traffic Indicators of on I-94 Interstate Highway
The goal of this project is to determine potential indicators of heavy traffic on I-94 Interstate highway. 
These indicators could be weather, time of the day, time of the week, etc.
The dataset used was from 2012 - 2018, which was made available by John Hogue, and can be downloaded from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume)

### Data Dictionary
The dataset have 9 columns

- `holiday`: This is a categorical data that refer to US National holidays plus regional holiday, Minnesota State Fair
- `temp`: This is a numerical data that refer to average temp in kelvin
- `rain_1h`: A numerical data whihc is the amount in mm of rain that occurred in the hour
- `snow_1h`: A numerical data which is the amount in mm of snow that occurred in the hour
- `clouds_all`: This is also a numerica whihc is the percentage of cloud cover
- `weather_main`: A categorical short textual data that describe the current weather
- `weather_description`: A categorical long textual data that describe the current weather
- `date_time`: DateTime Hour of the data collected in local CST time
- `traffic_volume`: Numeric Hourly I-94 ATR 301 reported westbound traffic volume

### Insights From the Analysis
The results of the analysis revealed that:
- Traffic is usually heavier during the warm months (March - October) and less heavy in the cold months (November - February)
- Generall, the traffic volume is usually higher during the working days, compare to weekends. 
- The rush hours for heavy traffic are 6am-7am and 3pm-4pm on daytime with records of over 6000 cars.
- Temperature does not have strong correlation with traffic volume.

