<<<<<<< HEAD

# README for Electric Vehicle Sales

This README provides details about the two datasets used for analyzing EV sales:

**`ev_dataset.csv`**  
**`petrol_price.csv`**  

**STATUS**  
**Completed**

## Dataset 1: Electric Vehicle Sales by State in India  
**Description:**  
Contains monthly data on Electric Vehicle (EV) sales across different states in India, categorized by vehicle type and class. Essential for analyzing EV adoption trends, state-wise policies, and market growth.

**File Name:** `ev_dataset.csv`

**Columns:**

- `Date`: The date when the data was recorded.
- `State`: The state where EV sales were reported (e.g., Maharashtra).
- `Vehicle_Class`: The class of the EV sold (e.g., E-RICKSHAW(P)).
- `Vehicle_Category`: The category of the EV sold (e.g., Three-Wheeler).
- `EV_Sales_Quantity`: The number of vehicles sold in the respective month and state.

**Time Period:**

- **Start:** 2018-01-01
- **End:** 2022-07-01
- **No. of months:** 53 months
- **No. of rows:** 54 rows

**Frequency:**

- Monthly

**Example Rows:**

| Date       | State      | Vehicle_Class | Vehicle_Category | EV_Sales_Quantity |  
|------------|------------|---------------|------------------|--------------------|  
| 2018-01-01 | Maharashtra| E-RICKSHAW(P) | Three-Wheeler    | 148                |  
| 2018-02-01 | Maharashtra| E-RICKSHAW(P) | Three-Wheeler    | 164                |  

---

## Dataset 2: Indian States Petrol Prices  
**Description:**  
Contains monthly average petrol prices for the top 15 states of India from 2017 to 2022. Enables analysis of fuel price trends and their comparison with EV adoption rates.

**File Name:** `petrol_price.csv`

**Columns:**

- `Month`: The month and year of the recorded petrol price.
- `State`: The state for which the petrol price was recorded (e.g., Maharashtra).

**Time Period:**

- **Start:** 2018-01-01 (Day is arbitrary, no specific day data available)
- **End:** 2022-10-01 (Includes an additional 3 months: August–October 2022)
- **No. of months:** 58 months
- **No. of rows:** 59 rows

**Frequency:**

- Monthly

**Example Rows:**

| Month      | State      | Petrol_Price |  
|------------|------------|--------------|  
| 2018-01-01 | Maharashtra| 77.87        |  
| 2018-02-01 | Maharashtra| 80.91        |  

---
=======
### README for electric\_vehicle\_sales

This README provides details about the two datasets used for analyzing EV\_sales

- **ev\_sales by State in India**  
- **Petrol\_price`.csv`**.


Status : Completed 

---

### Primary Data: Electric Vehicle Sales by State in India

- **Description**: This dataset contains information on Electric Vehicle (EV) sales across different states in India. It includes state-wise data, categorizing the types of EVs sold, which is essential for analyzing EV adoption trends, state-wise policies, and market growth in India.  
    
- **File Name**:ev\_dataset`.csv`  
    
- **Columns**:  
    
  - Date: The date when the data was recorded.  
  - State: The  EV sales were reported in Maharashtra.  
  - Vehicle\_Class: The class of the EV\_sold E-RICKSHAW(P)  
  - Vehicle category: The category of the EV sold Three-Wheeler.  
  - EV\_Sales\_Quantity: The number of vehicles sold in the respective year in Maharashtra state.  
    

    
- **Time Period**:  
    
  - Start:2018-01-01  
  - End: 2022-07-01  
  - No.of Months: 53  
  - No. of Rows:54


- **Frequency**:  
    
  - Monthly 


- **Example Rows**:  
    
  Date, State,vehicle\_class, vehicle\_category, EV\_Sales\_Quantity  
  01-01-2018,Maharashtra,E-RICKSHAW(P),3-Wheelers,148  
  01-01-2018,Maharashtra , E-RICKSHAW(P),3-Wheelers,164


  
---

### Secondary Data: Indian States Petrol Prices

- **Description**: This dataset provides petrol prices in the top 15 states of India from 2017 to 2022\. It includes monthly average petrol prices for each state, enabling analysis of fuel price trends and comparisons with EV adoption rates.  
    
- **File Name**: petrol\_price`.csv`.  
    
- **Columns**:


  - Month: The month and year of the recorded petrol price.  
  - State: The  Maharashtra state for which the petrol price was recorded.  
      
    

    
- **Time Period**:  
    
  - Start:  2018-01-01(taking 01 is random, don’t have day data)  
  - End:  2022-10-01 (Additional  3 months  data-From 8 to 10 )  
  - No.of months: 58 months   
  - No. of rows: 59


- **Frequency**:  
    
  - Monthly


- **Example Rows**:  
    
  date,Maharashtra,   
  2018-01-01,77.87  
  2018-02-01,80.91  
  


  
---

>>>>>>> df8be8020a06704234e045f8f67312e89adc09b5
