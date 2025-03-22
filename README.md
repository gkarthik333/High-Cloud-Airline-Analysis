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
## Key Metrics & Insights

* **Global Coverage:**
    * Analysis spans 104 countries, offering a global perspective on airline operations.
    * Includes data from 208+ airlines, providing a broad industry overview.
* **Operational Scale:**
    * 82 million miles traveled, reflecting extensive flight coverage.
    * 187 million passengers carried, highlighting the scale of operations.
    * 244 million available seats, indicating overall airline capacity.

## Dashboard-Specific Findings

### 1. Overall Performance (Dashboard 1)

* **Top Carrier:**
    *  Southwest Airlines leads with 34 million passengers, indicating strong market preference.
* **Operational Efficiency:**
    *  Year-wise bar chart (2008-2013) shows a close correlation between scheduled and performed departures, indicating high operational efficiency.

### 2. Load Factor Analysis (Dashboard 2)

* **Efficiency Trend:**
    *  Line graph shows an upward trend in load factor (seat occupancy) from 2008 to 2013, indicating increasing efficiency.
* **Temporal Variation:**
    *  Load factor varies by weekday and weekend, with weekdays showing slightly higher occupancy.
    *  Detailed load factor analysis by year, quarter, and month.
* **Carrier Performance:**
    *  Table comparing load factors across carriers, highlighting disparities and potential areas for improvement.
    *  Presence of NaN values indicates missing data that requires further investigation.

### 3. Flight Analysis (Dashboard 3)

* **Aircraft Type Distribution:**
    *  Majority of flights are operated by jet aircraft with 2 engines, optimizing for speed and efficiency.
    *  Turbo-prop and piston aircraft indicate a strong regional presence.
    *  Helicopter/STOL flights represent a niche market.
* **Distance Distribution:**
    *  Most flights are short-haul (under 999 miles), indicating a focus on regional travel.
    *  Limited long-haul operations observed.
* **Route Analysis:**
    *  Chicago to Detroit and Washington DC to Charlotte are identified as prominent routes, indicating high travel demand.

### 4. Interactive Flight Search (Dashboard 4)

* **Interactive Filtering:**
    *  Filters for origin/destination countries, states, and cities allow for granular flight selection.
* **Detailed Flight Information:**
    *  Table displays detailed flight information, including airline ID, name, code, month, day, day name, weekday/weekend, transported passengers, and available seats.
* **Example Airlines:**
    *  Demonstrates filtering using Hawaiian Airlines and Delta Airlines.
* **Geographic Visualization:**
    *  Interactive map of the United States and surrounding countries for visual flight exploration.



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
