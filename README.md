# High-Cloud-Airline-Analysis
This project presents a multi-faceted analysis of airline data, covering key performance indicators, passenger preferences, flight patterns, and operational efficiency. The analysis is visualized through a series of interactive dashboards, providing insights into various aspects of the airline industry.

Data Sources (Implied):

Airline flight data (including scheduled and performed departures, distances, aircraft types)
Passenger data (including preferences, travel dates, and origin/destination information)
Geographical data (for origin/destination locations)

## Data Model
This project utilizes a star schema for optimal airline data analysis. The central 'Maindata_final' fact table integrates data from ten dimension tables, including Airlines, Aircraft Types, and Markets. This data model enhances analysis performance by efficiently organizing flight operations and related information.
![Data Modelling](https://github.com/user-attachments/assets/b392fbcd-3a16-4b95-8ea1-758277f6c502)

## Key Metrics & Insights

* **Global Reach:** 104 Countries analyzed, showcasing a global perspective on airline operations.
* ✅ **Industry Overview:** 208 Airlines included, providing a broad industry overview.
* ✅ **Extensive Flight Coverage:** 82M miles traveled, reflecting extensive flight coverage.
* ✅ **Scale of Operations:** 187M passengers carried, emphasizing the scale of operations.
* ✅ **Overall Airline Capacity:** 244M available seats, indicating overall airline capacity.

## Top Findings from the Dashboard

* 📌 **Top 10 Carriers by Passenger Preference:**
    * Southwest Airlines leads the market, with 34 million passengers preferring the airline.
* 📌 **Year-wise Operational Performance (2008-2013):**
    * A bar chart visualizes the gap between scheduled vs. performed departures, highlighting airline efficiency trends.
* 📌 **Growing Efficiency in Airline Operations:**
    * A line graph tracks increasing load factors (seat occupancy rates), reflecting improved capacity utilization over time.
* 📌 **Consistent Passenger Demand:**
    * A pie chart reveals balanced travel patterns between weekdays and weekends, indicating steady demand across the week.
* 📌 **Performance Variation Across Airlines:**
    * A comparison table highlights disparities in load factors, shedding light on operational strengths and gaps.
* 📌 **Flight Distribution Based on Aircraft Group:**
    * Majority of flights are operated by Jet, 2-Engine aircraft, optimizing for speed and efficiency.
    * Turbo-prop and piston aircraft indicate a strong regional presence, while helicopter/STOL flights remain niche.
* 📌 **Flight Distribution Based on Distance:**
    * The data suggests a strong focus on short-haul travel (under 500 miles), with limited long-haul operations.
* 📌 **Busiest Routes (City-to-City Analysis):**
    * The Chicago to Detroit corridor emerges as the busiest route, showcasing high travel demand.
* 📌 **Geographical Filtering for Deeper Insights:**
    * Interactive maps and dropdowns empower users to filter flights by origin, destination, and region, providing localized insights.
* 📌 **Detailed Flight Records for Granular Analysis:**
    * A detailed table enables a deep dive into flight-level data, including airline names, passenger numbers, and operational trends.



![Arline Analysis](https://github.com/user-attachments/assets/5e7e8693-2aac-4402-b2da-3243921c87bb)
![Load Factor % Analysis](https://github.com/user-attachments/assets/19189aaf-96dd-4b43-9e71-d407a3df3354)
![Flights Analysis](https://github.com/user-attachments/assets/d82bd95a-5a73-4c9b-b4da-ec757542ad24)
![Find Your Flights](https://github.com/user-attachments/assets/0978d449-0e8f-49fe-9be9-860d30eef46d)

SQL Query:

Potential Further Analysis:
Detailed analysis of load factor variations across different routes and airlines.
Investigation of factors influencing passenger preferences.
Predictive modeling of flight delays or cancellations based on historical data.
Geospatial analysis of flight patterns and network optimization.
Analysis of the NaN values in the load factor table.
Analysis of monthly trends.


Tools used - Microsoft Excel, MySQL, Power BI
