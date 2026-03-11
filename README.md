
# DAX Demo – Advanced Calculations Using DAX in Power BI

## 📊 Project Overview

This project demonstrates advanced analytical calculations using **DAX (Data Analysis Expressions)** in **Microsoft Power BI**.
The goal of this project is to analyze **Sales and Returns data** and generate business insights using advanced DAX functions and time intelligence techniques.

All calculated results are displayed using a **Matrix visual**, grouped by **Region, Month, Product Category, and Customer Segment**.

---

## 🗂 Dataset Tables

The data model follows a **Star Schema** with the following tables:

* **Sales_Fact** – Main sales transactions
* **Returns_Fact** – Returned products data
* **Customer_Dim** – Customer details
* **Product_Dim** – Product information
* **Date_Dim** – Date dimension for time analysis
* **Region_Dim** – Regional information

---

## ⚙️ Key Features Implemented

### 1️⃣ Calculated Columns

* Profit Calculation (SalesAmount - Cost)
* Return Flag to identify returned items
* Customer Full Name creation
* Text transformations using **UPPER() and LEFT()**

### 2️⃣ DAX Measures

* Total Sales
* Total Cost
* Total Profit
* Return Rate
* Average Sales per Transaction

### 3️⃣ Quick Measures

* Year-over-Year Sales Growth
* Month-over-Month Sales Difference

### 4️⃣ Filter Context Functions

* **CALCULATE()**
* **FILTER()**
* **ALL()**

### 5️⃣ DAX Logical Functions

* **IF()**
* **SWITCH()** for sales category classification (Low, Medium, High)

### 6️⃣ Iterator Functions

* **SUMX()**
* **AVERAGEX()**

### 7️⃣ Time Intelligence

* **TOTALYTD()**
* **SAMEPERIODLASTYEAR()**
* **DATESINPERIOD()**
* Running Total using **CALCULATE() and DATESBETWEEN()**

### 8️⃣ Relationship Functions

* **RELATED()** used to pull dimension data into fact tables.

---

## 📈 Final Visualization

All analytical results are displayed using a **Matrix Visual Only**, grouped by:

* Region
* Month
* Product Category
* Customer Segment

No other visualizations were used as per the project requirement.

---

## 🛠 Tools & Technologies

* **Microsoft Power BI**
* **DAX (Data Analysis Expressions)**
* **Data Modeling (Star Schema)**

---

## 📂 Project File

`DAX Demo – Advanced Calculations Using DAX in Power BI.pbix`

---

## 🎯 Key Learning Outcomes

* Advanced DAX calculations and measures
* Time intelligence analysis
* Data modeling with fact and dimension tables
* Analytical reporting using Matrix visuals
