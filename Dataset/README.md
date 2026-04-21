# 📁 Dataset Description

## 📌 Overview

This dataset contains retail sales transaction data used to analyze customer behavior, product performance, and demand trends.

It is used as a **structured subset** to simulate Big Data analytics concepts such as aggregation, ETL processing, and SQL-based querying.

---

## 📊 Dataset Features

| Column Name      | Description                                             |
| ---------------- | ------------------------------------------------------- |
| Date             | Transaction date                                        |
| Customer_ID      | Unique identifier for each customer                     |
| Product_Category | Category of the product purchased                       |
| Payment_Method   | Mode of payment (Credit Card, Debit Card, Cash, PayPal) |
| Country          | Customer location                                       |
| Age              | Age of the customer                                     |
| Total_Purchases  | Number of items purchased                               |
| Total_Amount     | Total transaction value                                 |

---

## 🧹 Data Preprocessing

The dataset was cleaned and transformed before analysis:

* Converted `Date` to datetime format
* Handled missing values
* Removed `"Unknown"` categories
* Created new features:

  * `Month_Name`
  * `Avg_Order_Value`
  * `Total_Amount_M` (Revenue in Millions)

---

## ⚠️ Note

Due to size limitations on GitHub, a **sample dataset** is provided instead of the full dataset.

---

## 🎯 Purpose

This dataset is used to:

* Perform **SQL-based aggregation (GROUP BY, SUM)**
* Analyze sales trends and customer behavior
* Simulate **ETL pipelines and Big Data processing concepts**

---

## 📌 Usage

The dataset can be loaded using:

```python
import pandas as pd
df = pd.read_csv("retail_sample.csv")
```

---

## 🔒 Disclaimer

This dataset is used for **educational purposes only** and does not represent real business data.
