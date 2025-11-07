## HotelRevAI – Hotel Revenue Intelligence Dashboard

**Power BI–based Hotel Revenue, Occupancy & Profitability Analysis**

**Overview**

HotelRevAI is a data-driven Hotel Revenue Intelligence Dashboard built using Power BI, designed to help hotel management analyze, monitor, and optimize revenue, occupancy, cancellations, and profitability.
Using real-world hotel data, the dashboard visualizes key metrics such as ADR, RevPAR, Occupancy Rate, Profit Margin, and Seasonal Revenue Trends, enabling smart and timely decision-making.

**Key Features**
* Revenue Insights

* Total Revenue & Profit Margin

* ADR (Average Daily Rate)

* RevPAR (Revenue per Available Room)

* Seasonal revenue trends

* Operational Performance

* Occupancy Rate

* Lead Time

* Average Length of Stay (ALOS)

* Revenue per Guest

* Customer Intelligence

* Guest segmentation (Business vs Leisure)

* Repeat guest analysis

* Country-wise booking & revenue distribution

* Risk & Cancellation Analysis

* Cancellation Rate

* Revenue lost due to cancellations

* Seasonal cancellation patterns

* Interactive Dashboard Elements

* Slicers & filters for Date, Hotel, Season, Guest Type

* Cards, Line Charts, Pie Charts, Waterfall, Heatmaps, Maps

**Dataset Description**

Dataset: Hotel Bookings Expanded Dataset
Size: 163 rows × 38 columns

Contains:

* Booking & guest information

* Revenue & cost metrics

* Room performance attributes (ADR, RevPAR, Occupancy%)

* Seasonal & temporal fields

* Marketing and feedback data

**Data Preprocessing & Cleaning**

* Performed using Power Query & Excel

* Cleaning Steps

* Removed missing/duplicate entries

* Standardized date & numeric formats

* Filtered canceled bookings for final revenue calculations

* Transformations

* Normalized numeric fields

* Merged multiple tables into a relational model

**Feature Engineering (DAX & Power Query)**
-> Profit = TotalRevenue - TotalCosts

-> RevPAR = RoomRevenue / AvailableRooms

-> OccupancyPercentage = (ReservedRooms / AvailableRooms) * 100

-> RevenuePerGuest = TotalRevenue / (Check-ins + NewBookings)

**Exploratory Data Analysis (EDA)**
Major Findings

* Winter season generated the highest revenue & profits

* Leisure guests contributed ~57.69% of total revenue

* Business guests had higher ADR but shorter stays

* Average occupancy rate: 77.66% (strong performance)

* USA & Germany were top revenue-generating markets

* Cancellation spikes observed in off-peak months

**Dashboard Development (Power BI)**
* Data Modeling

* Established relationships between bookings, guests & performance tables

* DAX Measures

* ADR, RevPAR, Profit Margin, ALOS, Lead Time, Occupancy%

* Dynamic recalculations based on filters

**Visualizations Used**

* KPIs (Cards)

* Line Charts (Monthly Revenue/Profit)

* Pie Charts (Guest Type, Channels)

* Maps (Country-wise revenue)

* Waterfall Charts

* TreeMaps & Heatmaps

* Deployment

Published to Power BI Service for sharing and stakeholder access

**Key Insights**

* Winter is the most profitable season

* Leisure segment brings more bookings; business guests bring higher ADR

* Profit margin ~ 70.76%, showing strong cost efficiency

* Room pricing & occupancy strategies are well-optimized

* Direct & OTA channels show different revenue behaviors

* High engagement from international markets

**Conclusion**

HotelRevAI successfully transforms raw hotel booking data into a powerful, interactive revenue intelligence dashboard.
It enables hotels to:

* Identify revenue drivers

* Optimize pricing strategies

* Reduce loss from cancellations

* Improve occupancy management

* Support high-level strategic planning

**Future Enhancements**

* Machine Learning forecasting for revenue & occupancy

* Customer sentiment analysis from reviews

* Advanced segmentation using clustering

* Automated threshold alerts (KPIs)
