
# README for Flight Delay Prediction and Historical Weather Data

## Overview

This README provides details about the two datasets used for analyzing and predicting flight delays and their relationship to historical weather data.

**`flight_delay_processed.csv`**  
**`weather_processed.csv`**  

**STATUS**  
**Completed** 

### Dataset 1: Flight Delay  (Primary Dataset)

#### Description:
Contains daily data on flight schedules and delays. It includes essential features for understanding and predicting flight delays.

#### File Name:
flight_delay_processed.csv

#### Columns:
- **FlightDate**: The date of the flight.
- **OriginCityName**: The city of origin for the flight (e.g., New York, Los Angeles).
- **CRSDepTime**: Scheduled departure time in HHMM format.
- **DepTime**: Actual departure time in HHMM format.
- **DepDelay**: The delay in departure time (in minutes).

#### Time Period:
- **Start**: 2014-01-01.
- **End**: 2016-12-25.
- **Frequency**: Daily data.
- **No. of Rows**: 1604

#### Example Rows:

```plaintext 
FlightDate,OriginCityName,CRSDepTime,DepTime,DepDelay
01-01-2014,Los Angeles,1635,1653,18
02-01-2014,Los Angeles,1635,1628,-7
```

---

### Dataset 2:  Weather Data (Secondary Dataset)

#### Description:
Contains hourly historical weather data for various locations. The data is essential for analyzing the impact of weather conditions on flight delays.

#### File Name:
weather_processed.csv

#### Columns:
- **datetime**: The date and time of the weather observation.
- **humidity**: The relative humidity (in percentage).
- **Pressure**: Atmospheric pressure (in hPa).
- **Temperature**: Temperature (in Celsius).
- **wind_direction**: The direction of the wind (in degrees).
- **wind_speed**: Wind speed (in meters per second).

#### Time Period:
- **Start**: 2014-01-01 00:00.
- **End**: 2016-12-27  12:00.
- **Frequency**: Hourly data.
- **No. of rows** : 26198 (taking 2 days extra data)

#### Example Rows:

```plaintext 
datetime,humidity,Pressure,Temperature,wind_direction,wind_speed
01-01-2014 00:00,39,1017,290.41,230,1
01-01-2014 01:00,42,1017,288.09,230,1
```

## Status
- **Completed**

## Notes
Both datasets are pre-processed and used for flight delay prediction. The weather dataset acts as a secondary source to enhance the prediction by incorporating weather conditions.

---
