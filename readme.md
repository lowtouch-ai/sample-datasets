### README for NYC Yellow Taxi Trip Data

This README provides details about the two datasets used for analyzing dropoff\_datetime  
: **nyc\_yellow\_taxi\_trip data** and **nyc\_weather Data`.csv`**.

Status : Completed 

---

### Primary Data: NYC Yellow Taxi Trip Data

- **Description**: This dataset contains trip-level information from New York City’s Yellow Taxis, detailing count of every one hour. It is useful for analyzing taxi demand  
    
- **File Name**: nyc\_trip`.csv`  
    
- **Columns**:  
    
  - Date: The date and time when the meter was engaged.  
  - count: The number of trips happened  in the particular time period. 


- **Time Period**:  
    
  - Start:2016-01-01 00:00  
  - End: 2016-01-30 23:00  
  - No.of days: 30  
  - No. of Rows: 721


- **Frequency**:  
    
  - Hourly 


- **Example Rows**:  
  Date,count  
  01-01-2016 00:00,25270

---

### Secondary Data: NYC Weather Data

- **Description**: This dataset provides daily weather conditions for New York City . It includes detailed temperature, precipitation, and wind data. It can be used for weather trend analysis, forecasting, and understanding how weather impacts transportation systems like taxis​  
    
- **File Name**: nyc\_weather`.csv`.  
    
- **Columns**:

  - time: The date of the weather observation.  
  - temperature : The maximum temperature for the day (in °C).  
  - precipitation: Total precipitation for the day (in mm).  
  - rain: Only liquid precipitation of the preceding hour including local showers and rain  
  - Cloudcover (%):Total cloud cover as an area fraction  
  - windspeed\_10m (km/h): Wind speed at 10 meters above ground.  
  - winddirection\_10m (Â°): Wind direction at 10 meters above ground  
    

    
- **Time Period**:  
    
  - Start: 2016-01-01T00:00  
  - End: 2016-02-03T01:00   
  - No.of days: 34 days (4 days Extra from 31 to 3\)  
  - No.of Rows: 795 


- **Frequency**:  
    
  - Hourly 


- **Example Rows**:  
    
  time,temperature\_2m, precipitation,rain,cloudcover,,windspeed\_10m ,winddirection\_10m   
  2016-01-01T00:00,  7.6,            0,      0,         69,           10,                      296  
  


  
---

