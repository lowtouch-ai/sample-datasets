
# README for NYC Yellow Taxi Trip Data

This README provides details about the two datasets used for analyzing `dropoff_datetime`: `nyc_yellow_taxi_trip` data and `nyc_weather Data.csv`.

**Status**: Completed

## Primary Data: NYC Yellow Taxi Trip Data

**Description**: 
This dataset contains trip-level information from New York City’s Yellow Taxis, detailing count of every one hour. It is useful for analyzing taxi demand.

**File Name**: `nyc_trip.csv`

**Columns**:
- `Date`: The date and time when the meter was engaged.
- `count`: The number of trips happened in the particular time period.

**Time Period**:
- **Start**: 2016-01-01 00:00
- **End**: 2016-01-30 23:00
- **No. of Days**: 30
- **No. of Rows**: 721

**Frequency**:
- Hourly

**Example Rows**:
```
Date,count
2016-01-01 00:00,25270
```

## Secondary Data: NYC Weather Data

**Description**: 
This dataset provides daily weather conditions for New York City. It includes detailed temperature, precipitation, and wind data. It can be used for weather trend analysis, forecasting, and understanding how weather impacts transportation systems like taxis.

**File Name**: `nyc_weather.csv`

**Columns**:
- `time`: The date of the weather observation.
- `temperature`: The maximum temperature for the day (in °C).
- `precipitation`: Total precipitation for the day (in mm).
- `rain`: Only liquid precipitation of the preceding hour including local showers and rain.
- `Cloudcover (%)`: Total cloud cover as an area fraction.
- `windspeed_10m (km/h)`: Wind speed at 10 meters above ground.
- `winddirection_10m (°)`: Wind direction at 10 meters above ground.

**Time Period**:
- **Start**: 2016-01-01T00:00
- **End**: 2016-02-03T01:00
- **No. of Days**: 34 (4 extra days from Jan 31 to Feb 3)
- **No. of Rows**: 795

**Frequency**:
- Hourly

**Example Rows**:
```
time,temperature_2m,precipitation,rain,cloudcover,windspeed_10m,winddirection_10m
2016-01-01T00:00,7.6,0,0,69,10,296
```
