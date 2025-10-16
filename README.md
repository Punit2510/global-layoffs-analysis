# 📊 SQL Exploratory Data Analysis on World Layoffs Dataset

This project is an **Exploratory Data Analysis (EDA)** conducted entirely in **MySQL Workbench** to explore and understand global layoff trends using real-world data.  
It focuses on data cleaning, transformation, and deriving meaningful business insights from the **World Layoffs Dataset**.

---

## 🧠 Project Overview

The main goal of this project was to analyze global layoff patterns and uncover insights about companies, industries, and countries most affected.  
The process involved importing raw data, cleaning it for consistency, and executing SQL queries to extract key metrics and trends.

---

## ⚙️ Steps Followed

### 1. **Importing Raw Data**
- Imported the raw CSV dataset into **MySQL Workbench**.
- Verified the data schema and structure before further processing.

### 2. **Creating a Staging Table**
- Created a **staging table** mirroring the raw dataset.
- Used the staging table to perform data cleaning operations safely without altering the original data.

### 3. **Data Cleaning Process**
Performed rigorous data cleaning to ensure data accuracy and consistency:
- **Removed Duplicates:** Eliminated repeated records.  
- **Standardized Data:** Unified inconsistent formats and naming conventions.  
- **Handled Null/Blank Values:** Replaced or removed missing data where necessary.  
- **Removed Unnecessary Columns:** Dropped irrelevant fields to streamline analysis.

### 4. **Exploratory Data Analysis (EDA)**
Conducted SQL-based analysis to answer key business questions, including:

1. What was the **maximum number of layoffs in one day**?  
2. What was the **maximum percentage of layoffs in one day**?  
3. What was the **total number of layoffs by each company**?  
4. Which companies, if any, **laid off all employees**?  
5. What is the **time period** over which the data was collected?  
6. Which **industry** has the highest number of layoffs?  
7. Which **country’s companies** have the most layoffs?  
8. In which **year** did the most layoffs occur?  
9. What is the **rolling total of layoffs per month**?  
10. Which are the **top 5 companies per year** in terms of total layoffs?

---

## 🧾 Dataset Information

- **Dataset Name:** World Layoffs Dataset  
- **Format:** CSV  
- **Source:** Public dataset (open data repository)  
- **Columns Include:** Company, Industry, Country, Date, Total Laid Off, Percentage Laid Off, etc.   

---

## 🛠️ Tools & Technologies Used

- **MySQL Workbench** – for querying and data manipulation  
- **SQL** – for data cleaning, aggregation, and analysis  
- **Excel/CSV** – for importing and validating dataset  
- **Git & GitHub** – for version control and project documentation  

---

## 📈 Key Insights

- Certain **industries** (e.g., technology and finance) experienced the highest layoffs.  
- **Specific countries** consistently reported larger layoff volumes.  
- Temporal analysis revealed that **layoff patterns fluctuate sharply during global crises**.  
- Several companies reported **100% layoffs**, indicating complete shutdowns.  
- Identified **top 5 companies by layoffs per year**, providing valuable trend indicators.

---
