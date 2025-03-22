# High-Cloud-Airline-Analysis
This project presents a multi-faceted analysis of airline data, covering key performance indicators, passenger preferences, flight patterns, and operational efficiency. The analysis is visualized through a series of interactive dashboards, providing insights into various aspects of the airline industry.



## Data Model

* **Star Schema:** The core data model is a star schema, designed for analytical efficiency.
* **Fact Table:**
    * `Maindata_final`: The central fact table, containing measures related to flight operations.
* **Dimension Tables (10):**
    * `Carrier Groups`:
        * Key: `Carrier Group ID`.
    * `Aircraft Types`:
        * Key: `Aircraft Type ID`.
    * `Carrier Operating Region`:
        * Key: `Region Code`.
    * `Distance Groups`:
        * Key: `Distance Group ID`.
    * `Airlines`:
        * Key: `Airline ID`.
    * `Origin Markets`:
        * Key: `Origin Airport Market ID`.
    * `Destination Markets`:
        * Key: `Destination Airport Market ID`.
    * `Aircraft Groups`:
        * Key: `Aircraft Group ID`.
    * `Flight Types`:
        * Key: `Datasource ID`.
![Data Modelling](https://github.com/user-attachments/assets/b392fbcd-3a16-4b95-8ea1-758277f6c502)


## Key Metrics & Insights

### 1. Overall Performance 

* **Global Coverage:**
    * Analysis spans 104 countries, offering a global perspective on airline operations.
    * Includes data from 208+ airlines, providing a broad industry overview.
* **Operational Scale:**
    * 82 million miles traveled, reflecting extensive flight coverage.
    * 187 million passengers carried, highlighting the scale of operations.
    * 244 million available seats, indicating overall airline capacity.
* **Top Carrier:**
    *  Southwest Airlines leads with 34 million passengers, indicating strong market preference.
* **Operational Efficiency:**
    *  Year-wise bar chart (2008-2013) shows a close correlation between scheduled and performed departures, indicating high operational efficiency.
![Arline Analysis](https://github.com/user-attachments/assets/5e7e8693-2aac-4402-b2da-3243921c87bb)



### 2. Load Factor Analysis 

* **Efficiency Trend:**
    *  Line graph shows an upward trend in load factor (seat occupancy) from 2008 to 2013, indicating increasing efficiency.
* **Temporal Variation:**
    *  Load factor varies by weekday and weekend, with weekdays showing slightly higher occupancy.
    *  Detailed load factor analysis by year, quarter, and month.
* **Carrier Performance:**
    *  Table comparing load factors across carriers, highlighting disparities and potential areas for improvement.
    *  Presence of NaN values indicates missing data that requires further investigation.
![Load Factor % Analysis](https://github.com/user-attachments/assets/19189aaf-96dd-4b43-9e71-d407a3df3354)



### 3. Flight Analysis 

* **Aircraft Type Distribution:**
    *  Majority of flights are operated by jet aircraft with 2 engines, optimizing for speed and efficiency.
    *  Turbo-prop and piston aircraft indicate a strong regional presence.
    *  Helicopter/STOL flights represent a niche market.
* **Distance Distribution:**
    *  Most flights are short-haul (under 999 miles), indicating a focus on regional travel.
    *  Limited long-haul operations observed.
* **Route Analysis:**
    *  Chicago to Detroit and Washington DC to Charlotte are identified as prominent routes, indicating high travel demand.
![Flights Analysis](https://github.com/user-attachments/assets/d82bd95a-5a73-4c9b-b4da-ec757542ad24)



### 4. Interactive Flight Search 

* **Interactive Filtering:**
    *  Filters for origin/destination countries, states, and cities allow for granular flight selection.
* **Detailed Flight Information:**
    *  Table displays detailed flight information, including airline ID, name, code, month, day, day name, weekday/weekend, transported passengers, and available seats.
* **Example Airlines:**
    *  Demonstrates filtering using Hawaiian Airlines and Delta Airlines.
* **Geographic Visualization:**
    *  Interactive map of the United States and surrounding countries for visual flight exploration.
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
