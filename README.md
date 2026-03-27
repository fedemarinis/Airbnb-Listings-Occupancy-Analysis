# 🏘️ Airbnb Listings Occupancy Analysis  
**Data-Driven Insights to Improve Listing Performance**

---

## 📌 Overview

This project explores how data can be used to understand and improve the **occupancy performance of short-term rental listings**.

By analyzing large-scale Airbnb data, the goal is to identify the key factors that influence how often listings are booked and uncover actionable strategies to increase overall platform performance.

The analysis focuses on **Copenhagen listings**, using structured data workflows and visual analytics to translate raw data into business insights.

---

## 🎯 Objective

The main objective is to understand:

> How can occupancy rates be improved to increase booking activity and overall value generated from listings?

Occupancy plays a central role, as it directly impacts the number of nights booked and the overall economic performance of the platform :contentReference[oaicite:0]{index=0}.

---

## 📊 Key Insights

Several important patterns emerge from the analysis:

- 📉 **Price vs Occupancy**  
  Higher prices are consistently associated with lower occupancy levels

- ⭐ **Ratings Matter**  
  Listings with strong review scores achieve significantly better performance

- ⏱️ **Fast Responses Win**  
  Faster host response times are linked to higher booking rates

- 🔁 **Booking Experience**  
  Interaction and communication between hosts and guests influence decisions

- 📅 **Seasonality Effects**  
  Demand varies across the year, with clear high and low seasons

Additionally, a significant portion of listings remains underutilized, highlighting substantial improvement potential.

---

## 🧠 Approach

The project follows an end-to-end data workflow:

- Raw datasets were explored, cleaned, and standardized  
- Missing values and inconsistencies were handled carefully  
- Data was structured into a relational database for efficient querying  
- Analytical views were built to highlight key performance drivers  
- Insights were visualized through interactive dashboards  

A key assumption used in the analysis is that **unavailable listings are considered booked**, providing a consistent proxy for occupancy, even though it may slightly overestimate real values :contentReference[oaicite:1]{index=1}.

---

## 🗂️ Data

The analysis is based on three main datasets:

- Listing characteristics (properties, hosts, attributes)  
- Availability and pricing over time  
- User reviews and ratings  

Together, these sources allow for a comprehensive view of both **supply-side behavior** and **performance outcomes**.

---

## 🔍 What Drives Occupancy?

The analysis highlights two main groups of drivers:

### 1. Pricing Dynamics
- Strong negative relationship between price and occupancy  
- Opportunities to optimize pricing strategies across listings  

### 2. Non-Pricing Factors
- Guest satisfaction (ratings)
- Host responsiveness
- Communication quality and booking experience  

This shows that performance is not only about pricing, but also about **trust, quality, and interaction**.

---

## 💡 Key Takeaways

- Lowering prices can increase booking volume, but must be balanced carefully  
- Improving listing quality and host behavior can significantly boost performance  
- Even small improvements in key factors can lead to meaningful gains in occupancy  
- There is large unrealized potential due to unbooked nights across listings :contentReference[oaicite:2]{index=2}  

---

## 🛠️ Tools & Technologies

- Python (data cleaning & analysis)  
- Pandas (data manipulation)  
- SQL & PostgreSQL (data modeling)  
- Tableau (data visualization)  

---

## 🚀 Final Thoughts

This project shows how combining **data engineering, analysis, and visualization** can turn raw data into actionable insights.

Improving occupancy is not driven by a single factor, but by a combination of **pricing strategy, user experience, and host behavior**. Leveraging these elements together creates a strong opportunity to enhance overall performance.