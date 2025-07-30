# OLA-PROJECT

##  OLA PROJECT


###   1. Project Title / Headline
🛺 OLA Ride Analytics Dashboard: Monthly Operations & Performance Insights
An interactive Power BI report providing a comprehensive view of Ola’s July 2024 ride operations—covering bookings, vehicle‑type performance, revenue, cancellations, and ratings.

### 2. Short Description / Purpose
The OLA Ride Analytics Dashboard enables operations managers, business analysts, and senior leadership to explore daily and monthly trends in ride volumes, revenues, cancellation reasons, and customer/driver satisfaction across all vehicle categories. It’s designed to highlight opportunities for growth, areas of friction, and service‑quality improvements.

### 3. Tech Stack

Power BI Desktop – Primary authoring and visualization tool (.pbix).

Power Query – Data ingestion, cleaning, and transformation of raw trip logs.

DAX – Custom measures for KPIs (e.g., Total Booking Value, Cancellation Rate).

Data Modeling – Star schema linking bookings, customers, drivers, cancellations, payments, and ratings tables.

Data Sources – Flat files (.csv), SQL database extracts, and Excel snapshots for historical comparison.

### 4. Data Source

Bookings Table: One row per ride with Booking_ID, Customer_ID, Driver_ID, Vehicle_Type, Booking_Status, Booking_Value, Trip_Date, Distance.

Payments Table: Payment_Method per Booking_ID.

Cancellations Table: Cancellation_Reason, Canceled_By (Customer/Driver).

Ratings Table: Customer_Rating, Driver_Rating per completed ride.

Time Frame: July 1, 2024–July 30, 2024 (adjustable via slicer).

### 5. Features / Highlights

Business Problem
Rideshare operations generate vast amounts of data daily, but operational teams often lack a single, unified view to quickly identify booking trends, revenue drivers, cancellation hotspots, and service‑quality issues.

Goal of the Dashboard
Deliver a one‑stop, interactive analytics tool that empowers stakeholders to:

Monitor daily booking volumes and value.

Compare vehicle‑type performance and utilization.

Analyze revenue by payment method and top customers.

Investigate cancellation reasons and rates.

Track customer and driver ratings by vehicle category.

Walkthrough of Key Visuals

Overall Page

KPI Cards: Total Bookings (20 ,408), Total Booking Value (₹11 M).

Booking Status Breakdown: Pie chart showing Success (62%), Canceled by Driver (17.9%), Canceled by Customer (10.2%), Driver Not Found (9.9%).

Ride Volume Over Time: Line chart of daily booking count (650–720 rides/day).

Vehicle Type Page

Summary Table: For each category (Prime Sedan, Prime SUV, Prime Plus, Mini, Auto, Bike, E‑Bike):

Total Booking Value (₹1.54 M–₹1.67 M)

Success Booking Value (₹0.935 M–₹1.06 M)

Avg. Distance (10.0–25.7 km)

Total Distance (18 K–48 K km)

Revenue Page

Revenue by Payment Method: Bar chart showing Cash (₹3.8 M), UPI (₹2.8 M), Credit Card, Debit Card.

Top 5 Customers: Table of Customer_IDs contributing highest ride value in the period (sum = ₹14 ,981).

Ride Distance Trend: Daily sum of ride distances as proxy for usage intensity.

Cancellation Page

KPI Cards: Total Bookings, Successful Bookings, Canceled Bookings (5 ,735), Cancellation Rate (5.57%).

Canceled Rides by Customer: Pie chart of top reasons (e.g., “Driver not moving,” “Change of plans,” “Wrong address”).

Canceled Rides by Driver: Pie chart segmented by reasons (e.g., “Personal & car issues,” “Customer-related,” “Health-related”).

Ratings Page

Driver Rating by Vehicle Type: Table showing average driver scores (3.99–4.01).

Customer Rating by Vehicle Type: Table showing average customer scores (3.98–4.02).

Business Impact & Insights

Operational Efficiency: Spot days with low ride volumes to adjust driver incentives or marketing pushes.

Vehicle‑Type Optimization: Identify top‑performing categories (Prime Sedan) and underperformers (Auto with shorter avg. trips) to rebalance fleet allocations.

Revenue Growth: Encourage higher‑value payment methods (UPI, Credit Card) via promotions.

Cancellation Reduction: Tackle top customer cancellation reasons (driver delays, address issues) with targeted driver‑training or app UX improvements.

Customer Satisfaction: Compare ratings across segments to pinpoint service inconsistencies—e.g., slightly lower driver ratings on Mini vehicles.

### 6. Screenshots / Demos

Overall Overview – Alt text: “Dashboard homepage with date slicer (7/1–7/30), KPI cards for total bookings/value, booking status pie chart, and daily ride volume line chart.”
Example: image1(https://github.com/Prabhat4806/Ola_Dashboard-/blob/main/image1.png)

Vehicle Type Performance – Alt text: “Green‑bordered table listing seven vehicle types with booking values, success values, avg. distance, and total distance columns.”
Example: image2(https://github.com/Prabhat4806/Ola_Dashboard-/blob/main/image2.png)

Revenue Insights – Alt text: “Bar charts of revenue by payment method and daily ride distance; top‑5 customers table at top right.”
Example: image3(https://github.com/Prabhat4806/Ola_Dashboard-/blob/main/image3.png)

Cancellation Analysis – Alt text: “KPI cards for cancellations and two pie charts: customer vs. driver cancellation reasons.”
Example: image4(https://github.com/Prabhat4806/Ola_Dashboard-/blob/main/image4.png)
Ratings Summary – Alt text: “Tables of driver and customer average ratings per vehicle type, arranged side by side.”
Example: image5(https://github.com/Prabhat4806/Ola_Dashboard-/blob/main/image5.png)
