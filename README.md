https://github.com/AabshaarShaikh20/Call-Centre-Performance-Dashboard-Power-BI/blob/main/Call%20Center%20Dashboard.JPG

# 📞 Call Centre Performance Dashboard – Power BI

**United States Call Centre Dataset**

This Power BI project analyzes call performance across multiple call centers in the United States. It includes KPI tracking, call duration analysis, SLA response monitoring and a detailed grid view for exporting call records.

---

## 📌 **Project Overview**

The **Call Centre Dashboard** helps monitor call volume, service quality and agent responsiveness.
It is divided into two pages:

1️⃣ **Dashboard: Home** – High-level KPIs and charts

2️⃣ **Dashboard: Grid** – Detailed table view with export functionality

The report is built using real-world Power BI concepts including data cleaning, modeling, DAX calculations, time intelligence, custom charts, and navigation.

---

## 📂 **Dataset Information**

The dataset includes call records from various call centers across the **USA**.

### **Table 1 – Call Details**

| Column Name       | Description                                      |
| ----------------- | ------------------------------------------------ |
| id                | Unique call ID                                   |
| call_timestamp    | Date & time of the call                          |
| call_center       | Call center location                    |
| channel           | Communication channel (call-center, chatbot, email, web) |
| city              | City of the caller                               |
| state             | U.S. state                                       |
| customer_name     | Customer’s name                                  |
| reason            | Reason for the call(Billing Question, Payments, Service Outage)                              |
| sentiment         | Customer sentiment (Positive, Neutral, Negative) |
| response_time     | Response time in seconds(Above SLA, Below SLA, Within SLA)                         |
| call_duration_min | Call duration in minutes                         |

### **Table 2 – Date Table**

| Column Name | Description          |
| ----------- | -------------------- |
| Date        | Calender Date & time of the call       |
| Day        | Day name (Mon, Tue…)        |
| Day No        | Day number (1,2,...) |

---

## 🎯 **Dashboard 1: Home (KPIs & Charts)**

This page displays all the high-level performance indicators required for call center operations.

### **KPIs Included**

* **Total Calls**
* **Total Call Duration (Hours)**
* **Total Call Duration (Minutes)**
* **Average Call Duration (Minutes)**
* **Response Time Percentage (Calls Answered Within SLA)**

### **Charts Included**

* **Column Chart:** Total Calls By Day
* **Tree Chart:** Total Calls By Reason
* **Donut Chart:** Total Calls By Channel
* **Column Chart:** Total Calls By Sentiment
* **Bar Chart:** Total Calls By Call-center
* **Pie Chart:** Calls Answered Within SLA


---

## 📊 **Dashboard 2: Grid (Detailed View)**

A complete table displaying all call-level information.

### **Features**

* Displays every call record
* Supports filtering by:

  * Date
  * Channel
  * City
* Clean, user-friendly layout

---

## 🛠️ **Power BI Skills Demonstrated**

### ✔ **Data Cleaning**

### ✔ **Power Query**

### ✔ **Data Modeling**

### ✔ **DAX Calculations**

### ✔ **Visual Development**

### ✔ **Report Design**

---

## 🚀 **Purpose of This Project**

This dashboard helps analyze:

* Performance of call centers across US regions
* Customer sentiment and common reasons for contact
* Efficiency of agents responding within SLA
* Overall call duration and trends
* Operational insights for workforce planning

---

## 📁 **Files Included**

* `.pbix` report file
* Dataset CSV files
* README documentation (this file)
* Images/Screenshots of dashboards 

---

