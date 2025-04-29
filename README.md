Project Overview
This project presents a comprehensive Hospitality Analytics Dashboard that provides valuable insights into hotel performance across multiple cities. Built using a dataset covering May to July, the dashboard allows users to analyze key performance indicators (KPIs) such as Revenue, Occupancy %, ADR, RevPAR, DSRN, and Realisation %, helping hospitality stakeholders make data-driven decisions.

Dataset Description:
The dataset consists of five structured CSV files with the following schema:

1. dim_date
date: Full date

mmm yy: Month-year format

week no: Unique week number

day_type: Weekend or Weekday

2. dim_hotels
property_id: Unique hotel identifier

property_name: Hotel name

category: Hotel class (Luxury/Business)

city: Location of the hotel

3. dim_rooms
room_id: Room type (RT1 to RT4)

room_class: Room category (Standard to Presidential)

4. fact_aggregated_bookings
property_id: Hotel ID

check_in_date: Date of check-in

room_category: Room type

successful_bookings: Number of successful bookings

capacity: Maximum available rooms

5. fact_bookings
booking_id: Unique booking ID

property_id: Hotel ID

booking_date, check_in_date, check_out_date: Booking and stay dates

no_guests: Number of guests per booking

room_category: Room type

booking_platform: Source of booking (online, travel agency, etc.)

ratings_given: Customer rating

booking_status: Cancelled / Checked Out / No Show

revenue_generated: Gross revenue

revenue_realized: Net revenue (after deductions)

Key Metrics Visualized
Revenue: Total revenue across hotels

RevPAR (Revenue Per Available Room)

ADR (Average Daily Rate)

Occupancy %

DSRN (Daily Sold Room Nights)

Realisation %

Revenue by Hotel Category (Luxury vs. Business)

Trends Over Time (by Week)

Performance by City and Property

Realisation % and ADR by Booking Platform

Weekday vs. Weekend Metrics

Tools & Technologies
Power BI – for data modeling and dashboard visualization

Excel – for exploratory data analysis and metric calculation

📷 Dashboard Preview
![image](https://github.com/user-attachments/assets/786d49c4-2c67-4586-8597-7cde6e753571)

🚀 How to Run
Open Power BI Desktop

Load the dataset files (CSV format as per schema)

Load or import the .pbix Power BI dashboard file (if available)

Interact with filters such as Room Type, City, and Date Range

Explore KPIs and trends using the visualizations

📈 Key Insights
Business hotels generate ~62% of revenue, while Luxury accounts for ~38%

Realisation % and ADR vary significantly across booking platforms

Higher weekend occupancy and RevPAR compared to weekdays

Hyderabad and Delhi properties show consistently higher ADR and occupancy

🔮 Future Enhancements
Add predictive analytics for occupancy forecasting

Integrate real-time data feeds for dynamic updates

Include customer sentiment analysis from textual reviews

Let me know if you'd like 
