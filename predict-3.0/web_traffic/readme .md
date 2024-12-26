### README for Web\_Traffic

This README provides details about the two datasets used for analyzing Web\_traffic count

- **web\_traffic**   
- **daily\_website\_visitors**.

Status : Completed 

---

### Primary Data: Web\_traffic

- **Description**: This dataset contains time series data of **Daily** web traffic for various Wikipedia pages. It is useful for analyzing web traffic trends, identifying patterns, and building forecasting models.  
    
- **File Name**: web\_traffic`.csv`  
    
- **Columns**:

  - Date: The date of web traffic measurement (YYYY-MM-DD).  
  - Visits: The number of visits (web traffic) to the page on that date.  
    

    
- **Time Period**:  
    
  - Start:2020-01-20  00:00:00  
  - End: 2020-05-17  12:30:00  
  - No. of days: 119   
  - No. of rows:  2794


- **Frequency**:  
    
  - Hourly


- **Example Rows**:  
    
  Timestamp,TrafficCount  
  20-01-2020  00:00:00,487  
  20-01-2020  00:30:00,385


  
---

### Secondary Data: Daily Website Visitors Dataset

- **Description**: This dataset provides **Daily** visitor counts for various websites. It is useful for understanding web traffic trends, peak visit times, and creating predictive models for future visits.  
- **File Name**: website\_visitors`.csv`.  
    
- **Columns**:

  - Day: Day of week in text form (Sunday, etc.)  
  - Date:Date in mm/dd/yyyy format  
  - Page.Loads: Daily number of pages loaded  
  - Unique.Visits: Daily number of visitors from whose IP addresses there haven't been hits on any page in over 6 hours  
  - First.Time.Visits: Number of unique visitors who do not have a cookie identifying them as a previous customer  
  - Returning.Visits: Number of unique visitors minus first time visitors

- **Time Period**:  
    
  - Start: 2020-01-20  
  - End: 2020-05-25  
  - No. of days: 127 days (8 days more than Primary Dataset)   
  - No. of rows: 128 


- **Frequency**:  
    
  - Daily 

- **Example Rows**:  
    
  Day,Date,Page.Loads,Unique.Visits,First.Time.Visits,Returning.Visits  
  Monday,20-01-2020,3715,2948,2505,443  
  Tuesday,21-01-2020,4459,3501,3017,484  
  


  
---

