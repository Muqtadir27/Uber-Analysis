🚖 Uber Trip Analysis – Power BI -  Dashboard
📌 Project Overview

The Uber Trip Analysis dashboard provides in-depth insights into Uber's trip data for June 2024, helping stakeholders make data-driven decisions regarding operations, pricing, and resource allocation.
Using Power BI, the project uncovers booking trends, revenue patterns, trip efficiency, location hotspots, and demand variations over time.

🎯 Business Requirement

The goal of this project is to:

Analyze Uber trip performance in terms of bookings, revenue, trip distance, and trip time.

Identify trends across vehicle types, payment methods, and locations.

Optimize operations by understanding peak hours, high-demand areas, and preferred vehicle types.

📊 Key KPIs Tracked

Total Bookings – How many trips were booked over the given period.

Total Booking Value – Total revenue from all bookings.

Average Booking Value – Average revenue per booking.

Total Trip Distance – Combined distance covered by all trips.

Average Trip Distance – Typical distance customers travel per trip.

Average Trip Time – Mean trip duration.

🗂 Dashboard Structure
1️⃣ Overview Analysis

Total Bookings by Payment Type – e.g., Uber Pay, Cash.

Total Bookings by Trip Type – Day vs. Night trips.

Vehicle Type Analysis – Bookings, revenue, and distances for UberX, UberXL, Uber Green, Uber Comfort, and Uber Black.

Location Insights:

Most Frequent Pickup: Penn Station/Madison Sq West

Most Frequent Drop-off: Upper East Side North

Farthest Trip: Lower East Side → Crown Heights North (144.1 miles)

Top 5 Booking Locations with their most preferred vehicle type.

2️⃣ Time Analysis

Booking Value by Pickup Time – Identifies daily peak demand periods.

Booking Value by Day Name – Shows weekday vs. weekend trends.

Booking Value by Hour & Day Heatmap – Highlights busiest hours for each day.

3️⃣ Details Tab

Full Data Grid View – Displays trip-by-trip details:

Trip ID, Date, Time, Vehicle, Payment Type, Passengers, Distance, Value, Pickup Location, Total Bookings.

Drill-Through Functionality – Access filtered records from other visuals.

Toggle View – Switch between filtered and full dataset.

📈 Insights Derived

High-Volume Days: Wednesday & Saturday show peak revenues.

Peak Demand Hours: 8 AM – 6 PM generate the highest booking values.

Popular Vehicle: UberX accounts for the largest share of bookings and revenue.

Short Trips Dominance: Average trip distance is 3 miles with a 16-minute duration.

Location Hotspots: Penn Station/Madison Sq West is the most common pickup point.

⚙️ Implementation Highlights

Dynamic Measure Selector – Allows switching KPIs across all visuals.

Conditional Formatting – Highlights high and low KPI values.

Slicers – Filter by date, city, vehicle type, and payment method.

Interactive Bookmarks – For switching between overview and detail modes.

Export Button – Download raw trip data in CSV/Excel format.

📂 Dataset

Source: Uber trip dataset (June 2024)

Size: 103.7K records

Fields: Trip ID, Pickup Date & Hour, Vehicle Type, Payment Type, Distance, Value, Pickup Location, etc.

🛠 Tools & Technologies

Power BI – Dashboard creation & interactive analysis.

DAX – Calculated measures for KPIs & dynamic visuals.

Data Modeling – Relationships between trip, location, and time data.

Conditional Formatting & Tooltips – Enhanced user experience.

💡 Expected Outcomes

✔ Detect booking & revenue patterns.
✔ Compare trip trends by vehicle, payment, and location.
✔ Optimize driver allocation & pricing strategies.
✔ Improve customer experience via targeted operational decisions.

📷 Dashboard Preview

Overview Analysis


Time Analysis


Details Tab
