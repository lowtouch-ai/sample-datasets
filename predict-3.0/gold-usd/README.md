# README for Gold Price

This README provides details about the two datasets used for analyzing gold prices: 
- `daily_gold_price.csv`
- `inr_to_usd_exchange_rate.csv`

## Status
**Completed**

---

## Dataset 1: Gold Price

**Description:**  
Contains daily gold price data from 2014 to 2022, including price fluctuations, trading volume, and percentage changes in price.

**File Name:** `daily_gold_price.csv`

**Columns:**
- **timestamp:** The time of the observation (daily intervals).
- **Price:** The closing price of gold (in USD per ounce).
- **Open:** The opening price of gold (in USD per ounce).
- **High:** The highest price of gold during the day.
- **Low:** The lowest price of gold during the day.
- **Volume:** The total trading volume for gold (in ounces).
- **Chg%:** The percentage change in gold price from the previous day.

**Time Period:**
- **Start:** 2014-01-01
- **End:** 2022-08-05
- **No. of days:** 3165 days - 2228 rows

**Frequency:**
- Daily (1 day interval, only weekdays data)

**Example Rows:**
```
Date, Price, Open, High, Low, Volume, Chg% 
2014-01-06, 29119, 29300, 29395, 29051, 24380, -0.55
```

---

## Dataset 2: INR to USD Exchange Rate

**Description:**  
Contains daily exchange rate data between the Indian Rupee (INR) and the US Dollar (USD), along with trading volume for the INR/USD pair.

**File Name:** `inr_to_usd_exchange_rate.csv`

**Columns:**
- **timestamp:** The time of the observation (daily intervals).
- **Open:** The opening INR to USD exchange rate.
- **High:** The highest exchange rate during the day.
- **Low:** The lowest exchange rate during the day.
- **Close:** The closing INR to USD exchange rate.
- **Adj Close:** The adjusted closing exchange rate (after accounting for corporate actions).
- **Volume:** The volume of INR to USD traded.

**Time Period:**
- **Start:** 2014-01-01
- **End:** 2022-08-05 (Weekend and holidays not added)
- **Test Data:** 2022-08-15 (8-15 days)
- **No. of Days:** 2250 rows (6 days more)

**Frequency:**
- Daily (1 day interval)

**Example Rows:**
```
Date, Open, High, Low, Close, Adj Close, Volume 
2003-12-01, 0.021878, 0.021923, 0.021868, 0.021877, 0.021877, 0
```