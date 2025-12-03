# 📊 AirBnB Monthly Dashboard – Tableau Project 

<img width="1100" height="603" alt="Airbnb Dashboard" src="https://github.com/user-attachments/assets/fb80895f-b63f-4901-a5b6-c730e236363d" />

---

## 📝 **1. Project Overview & Business Context**

**Report Name:** **AirBnB Monthly Dashboard**

**Purpose/Goal:**
To provide a comprehensive monthly analysis of AirBnB rental performance, focusing on key insights into revenue trends, rental pricing behavior, listing availability, and customer engagement. The dashboard supports informed decision-making by analyzing patterns across different zip codes and house types (number of bedrooms).

**Target Audience:**

* Property Managers
* Real Estate Analysts
* Company Leadership & Strategy Teams
* Revenue & Pricing Analysts

---

## 🔗 **2. Data Source and Connection Details**

**Primary Data Source:**

* **PostgreSQL Database** (or similar centralized transactional database containing reservation, revenue, and listing information)

**Authentication Method:**

* Connection secured using **Personal Access Token** or **Database Service Account credentials**, managed through Tableau Cloud/Server connection security settings.

**Data Gateway:**

* **No Gateway Required**
  Data is cloud-hosted and directly accessible by Tableau Cloud/Server without on-premise gateway dependence.

---

## 📂 **3. Report Structure and Key Metrics**

**Number of Pages/Tabs:**

* **1** (Single consolidated interactive dashboard)

### **Key Areas of the Dashboard**

The AirBnB Monthly Dashboard includes the following analytical sections:

* **Avg. Rent by Zipcode**
  Horizontal bar chart visualizing average rent across different zip codes.

* **Revenue by Month**
  Time-series line chart showing monthly revenue over time, highlighting fluctuations and seasonal trends.

* **Revenue by House Type (Number of Bedrooms)**
  Bar chart comparing revenue contribution across property types.

* **Reviews per Month by House Type**
  Bar chart showing average review activity per bedroom category.

* **Avg. Rent by House Type**
  Line chart trending average rent as bedroom count increases.

* **Distinct Count of House Listings**
  Tabular summary showing the number of listings by bedroom count.

### **Core Metrics (KPIs)**

* **Total & Monthly Revenue**
* **Average Rent (By Zipcode & House Type)**
* **Reviews per Month**
* **Distinct Count of Listings**
* **Revenue Contribution by Bedroom Category**

### **Visualizations of Note**

* **Time-Series Line Chart:** Revenue over month
* **Bar Charts:** Avg. Rent by Zipcode, Revenue by Bedroom type, Review frequency
* **Trend Line Chart:** Avg. Rent vs. Number of Bedrooms
* **Tabular Summary:** Listing count distribution

---

## 🔄 **4. Data Refresh and Maintenance**

**Refresh Frequency:**

* **Daily at 4:00 AM EST**

**Dataset Name in Tableau Service:**

* **AirBnB_Listings_Revenue_Monthly_Extract**

---

## ⚙️ **5. Technical Specifications**

**Tableau Version Used:**

* **Tableau Desktop 2024.1** (or latest stable version)

**Row-Level Security (RLS):**

* **No RLS Implemented**
  Data is aggregated and intended for organization-wide visibility.

---

## 📌 **Summary**

The **AirBnB Monthly Dashboard** is a unified reporting solution designed to give stakeholders a data-driven view of rental performance across zip codes and house types. Through intuitive visualizations and well-structured metrics, the dashboard helps teams assess pricing strategies, monitor booking patterns, and identify opportunities for improved revenue performance.
