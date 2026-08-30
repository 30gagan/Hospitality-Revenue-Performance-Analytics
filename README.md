# 🏨 Hospitality Revenue & Performance Analytics

## 📌 Project Overview

An end-to-end **Power BI analytics project** analyzing revenue and operational performance for **Atliq Grands**, a 5-star hotel chain across major Indian cities.

The project evaluates key hospitality KPIs including **Revenue, RevPAR, ADR, Occupancy %, Realization %, and Cancellation %** to identify performance gaps, pricing opportunities, and booking-channel trends.

## 🎯 Business Objective

The analysis aims to answer key business questions such as:

* Which properties are performing well or underperforming?
* How are Revenue, RevPAR, ADR, and Occupancy changing over time?
* Which booking platforms deliver better realization?
* How does performance differ between weekdays and weekends?
* Where are the opportunities to improve pricing and revenue?

## 🗂️ Dataset

The analysis covers **3 months of hotel booking and capacity data (May–July)** across:

* **Cities:** Bangalore, Mumbai, Delhi & Hyderabad
* **Hotel Categories:** Business & Luxury
* **Booking Channels:** Direct, MakeMyTrip, LogTrip, Tripster, Journey & Others

### Data Model

A **Star Schema** was created using:

* `fact_bookings`
* `fact_aggregated_bookings`
* `dim_hotels`
* `dim_rooms`
* `dim_date`

## 🔧 Tools & Technologies

* **Power BI** – Dashboard & visualization
* **Power Query** – Data cleaning & transformation
* **DAX** – KPI calculations & WoW analysis
* **Data Modeling** – Star schema & relationships

## 📊 Key KPIs

* Revenue
* RevPAR (Revenue Per Available Room)
* ADR (Average Daily Rate)
* Occupancy %
* Realization %
* Cancellation %
* DSRN / DBRN / DURN

## 🔍 Key Insights

* **Pricing remained relatively flat** despite changes in occupancy and demand, indicating an opportunity for dynamic pricing.
* **Weekend demand** presented opportunities for differentiated pricing and improved RevPAR.
* **Underperforming properties**, including AtliQ Grands Bangalore, require targeted operational improvements.
* Properties with **lower customer ratings** showed weaker occupancy and higher cancellation levels.
* Booking-channel analysis highlighted opportunities to **increase direct bookings and reduce dependence on high-commission OTAs**.

## 💡 Business Recommendations

* Introduce **dynamic and weekend-based pricing**.
* Focus on improving service quality at underperforming properties.
* Improve consistency of hotel listings across booking platforms.
* Increase **direct bookings** through loyalty programs, offers, and bundled benefits.
* Monitor property and channel-level KPIs regularly through the Power BI dashboard.

## 📊 Dashboard

The interactive Power BI dashboard provides:

* Executive KPI overview
* Property-level performance analysis
* Revenue by hotel category
* RevPAR, ADR & Occupancy trends
* Booking-platform comparison
* Weekday vs Weekend analysis

## 📁 Project Structure

```text
Hospitality-Revenue-Performance-Analytics/
│
├── README.md
├── PowerBI/
│   └── Hospitality_rev_dashboard.pbix
├── Dataset/
├── Presentation/
└── Screenshots/
```

## 🚀 Project Outcome

This project demonstrates practical skills in **data cleaning, data modeling, DAX, KPI development, Power BI dashboarding, and business-oriented data analysis**, with a focus on converting raw hospitality data into actionable revenue-management insights.
