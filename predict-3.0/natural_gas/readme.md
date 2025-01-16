
# README for Natural Gas Price

This README provides details about the two datasets used for analyzing Natural gas price:

**`natural_gas_price`**  
**`u.s.natural_gas_production`**  

**STATUS**  
**Completed**

## Primary Data: Natural_gas_price  
**Description:**  
Contains historical daily natural gas price data, including spot prices, percentage changes, and other key indicators for analyzing price trends.

**File Name:** `natural_gas_price.csv`

**Columns:**

- `Date`: The date of the observation (daily intervals).
- `Price`: Daily spot price of natural gas.

**Time Period:**

- **Start:** 2008-06-02
- **End:** 2018-05-25 (only weekdays data)
- **No. of days:** 3644
- **No. of rows:** 2643

**Frequency:**

- Daily

**Example Rows:**
```plaintext
Date, Price
2008-06-02,7.83
2008-06-03,7.84
```

---

## Secondary Data: Gas Production Dataset  
**Description:**  
Contains Monthly natural gas production data in the U.S. by region, measured in million cubic feet (MMcf).

**File Name:** `gas_production.csv`

**Columns:**

- `Date`: The observation date (monthly intervals).
- `Region`: The name of the production region in the U.S.
- The total volume of natural gas produced in million cubic feet for the specified month and region.

**Time Period:**

- **Start:** 2008-06-01
- **End:** 2018-06-01
- **No. of months:** 122 months (1 month extra than primary dataset)
- **No. of rows:** 122 rows

**Frequency:**

- Monthly

**Example Rows:**
```plaintext
Date,U.S.,Alaska,Arkansas,Kansas,Other States,Federal Offshore--Gulf of Mexico,Wyoming,West Virginia,Utah,Pennsylvania,Texas,Oklahoma,Ohio,North Dakota,New Mexico,Montana,Louisiana,Colorado,California
2008-06-01,70626,8875,1196,1024,2995,7339,6839,670,1198,540,21446,5241,224,243,3975,323,3989,3576,932
2008-07-01,71137,8375,1256,1034,3150,7468,6940,674,1200,512,21547,5256,220,243,4179,324,4008,3834,919
```

---
