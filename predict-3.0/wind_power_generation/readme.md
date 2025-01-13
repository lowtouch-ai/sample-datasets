# README for Wind Turbine Power Generation Forecasting  

This README provides details about the two datasets used for analyzing and forecasting wind turbine power generation:  

**`wind_generation.csv`**  
**`WeatherData.csv`**  

**STATUS**  
**Completed**  

## Dataset 1: Wind Turbine Power Generation Data  
**Description:**  
Contains hourly data on wind turbine power generation. It provides essential insights for understanding and predicting wind energy production trends across four different locations.  

**File Name:** `wind_generation.csv`  

**Columns:**  

- `Time`: The timestamp for the recorded data (e.g., 2017-01-02 00:00).  
- `Power`: The wind turbine power generation value (measured in kilowatts, kW).  
  

**Time Period:**  

- **Start:** 2017-01-02 00:00  
- **End:** 2016-12-30 12:00.
- **No. of rows** 35017
- **Frequency:** Hourly  

**Example Rows:**  

```plaintext  
Time,  Power  
2017-01-02 00:00,  0.163495886
2017-01-02 01:00, 0.142395886
```  

---

## Dataset 2: Weather Data for Wind Turbine Locations  
**Description:**  
Contains hourly meteorological data recorded from the same locations as the wind turbines. Includes key variables such as temperature, wind speed, and wind direction, which directly impact wind power generation.  

**File Name:** `WeatherData.csv`  

**Columns:**  

- `Time`: The timestamp for the recorded meteorological data (e.g., 2017-01-02 00:00).   
- `Temp_2m`: The ambient temperature at the recording time (measured in °C).
- `RelHum_2m`: The relative humidity at the recording time(as a percentage).
-`DP_2m`: Dew point at 2 meters (in degrees Celsius)
- `Wind_Speed`: The wind speed recorded at the location (measured in m/s).  
- `Wind_Direction`: The direction of the wind recorded (measured in degrees).  

**Time Period:**  

- **Start:** 2017-01-02 00:00  
- **End:** 2016-12-31 12:00.  
- **No. of rows** 35041
- **Frequency:** Hourly  

**Example Rows:**  

```plaintext  
Time, Temp_2m,RelHum_2m,DP_2m,WS_10m,WS_100m,WD_10m,WD_100m,WG_10m 
2017-01-02 00:00,28.27960022,84.66420479,24.07259522,1.605389169,1.267799417,145.0516826,161.0573147,1.336515074 
2017-01-02 01:00, 28.17960022,85.66420479,24.27259522,2.225389169,3.997799417,150.0516826,157.0573147,4.336515074 
```  
