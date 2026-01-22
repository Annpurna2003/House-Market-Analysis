# 🏠 House Market Analysis Dashboard

This repository contains a **House Market Analysis** project built using real-estate transaction data. The project focuses on analyzing housing sales trends, pricing behavior, regional performance, and house-type insights using **Power BI**.

---

## 📊 Dataset Overview

The project uses **large-scale housing datasets** to simulate real-world analytics:

* 📁 **Dataset Sizes**:
=
  * Full dataset: **100,000+ records (1 lakh rows)** for detailed analysis

* 📌 **Nature of Data**:

  * Residential property sales data
  * Covers multiple regions, cities, house types, and sales types

---

## 🧾 Dataset Columns

The dataset contains the following key columns:

| Column Name                           | Description                                                    |
| ------------------------------------- | -------------------------------------------------------------- |
| `date`                                | Transaction date of the house sale                             |
| `quarter`                             | Financial quarter (e.g., 1996Q3)                               |
| `house_id`                            | Unique identifier for each house                               |
| `house_type`                          | Type of house (Apartment, Villa, Townhouse, Farm, Summerhouse) |
| `sales_type`                          | Mode of sale (regular_sale, auction, family_sale, other_sale)  |
| `year_build`                          | Year the house was constructed                                 |
| `purchase_price`                      | Final purchase price                                           |
| `%_change_between_offer_and_purchase` | Price negotiation percentage                                   |
| `no_rooms`                            | Number of rooms                                                |
| `sqm`                                 | Total area in square meters                                    |
| `sqm_price`                           | Price per square meter                                         |
| `address`                             | Property address                                               |
| `zip_code`                            | Postal code                                                    |
| `city`                                | City name                                                      |
| `area`                                | Area/Island (Bornholm, Fyn & Islands, Zealand, Jutland)        |
| `region`                              | Region of Denmark                                              |
| `nom_interest_rate%`                  | Nominal interest rate                                          |
| `dk_ann_infl_rate%`                   | Annual inflation rate                                          |
| `yield_on_mortgage_credit_bonds%`     | Mortgage bond yield                                            |

---

## 📈 Dashboard Pages & Insights

### 1️⃣ House Market Analysis

* Year-over-Year (YoY) Sales Growth by Sales Type
* Offer Price vs Purchase Price relationship
* Median Sales Price Change by Region
* Units Sold (Latest Year & Quarter)
* Last 12 Months (LTM) Sales Value

📌 **Key Insight**: Regular sales dominate volume, while family sales show negative growth.

---

### 2️⃣ Sales Performance

* Total Sales by Region
* Top Cities by Purchase Price
* Average Price per SQM by Region
* Offer-to-SQM Ratio by Sales Type
* Detailed Year–Quarter–Month Sales Table

📌 **Key Insight**: Zealand and Jutland contribute the highest sales value.

---

### 3️⃣ House Type Analysis

* Average Offer Price vs Purchase Price by House Type
* Impact of Inflation, Interest Rate & Yield
* Average SQM vs SQM Price per House Type
* Interactive Filters: Area, City, Sales Type, Region

📌 **Key Insight**: Apartments have the highest SQM price, while farms have the largest area.

---

## 🛠 Tools & Technologies Used

* **Power BI** – Data visualization & dashboarding
*  **CSV** – Data source
* **MYSQL**-Data Cleaning
* **AWS**-Data Storage
* **DAX** – Measures & KPIs
* **Data Modeling** – Star schema design

---

## 🎯 Use Cases

* Real estate market trend analysis
* Pricing strategy evaluation
* Regional performance comparison
* Investment decision support
* Portfolio & demand analysis

---




## 👤 Author

**Annpurna Srivastava**
CSE Graduate | Data Analyst | Full Stack Developer

---

## ⭐ Feedback

If you find this project useful, please ⭐ the repository and share your feedback!
