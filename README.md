# High-Cloud-Airline-Analysis
This project presents a multi-faceted analysis of airline data, covering key performance indicators, passenger preferences, flight patterns, and operational efficiency. The analysis is visualized through a series of interactive dashboards, providing insights into various aspects of the airline industry.

Data Sources (Implied):

Airline flight data (including scheduled and performed departures, distances, aircraft types)
Passenger data (including preferences, travel dates, and origin/destination information)
Geographical data (for origin/destination locations)

## Data Model
This project utilizes a star schema for optimal airline data analysis. The central 'Maindata_final' fact table integrates data from ten dimension tables, including Airlines, Aircraft Types, and Markets. This data model enhances analysis performance by efficiently organizing flight operations and related information.


Key Insights & Analysis:

1. Overall Performance (Dashboard 1):
The airline data encompasses a significant scope, with 104 countries and over 208 airlines represented.
The total distance traveled is 82 million miles, with 187 million passengers transported.
The total available seats were 244 million.
Southwest Airlines is the top carrier by passenger preference, with 34 million passengers.
The year-wise operational performance shows a close correlation between scheduled and performed departures, indicating operational efficiency.

2. Load Factor Analysis (Dashboard 2):
The load factor (percentage of seats filled) shows an upward trend from 2008 to 2013, indicating increasing efficiency.
The load factor varies by weekday and weekend, with a slightly higher percentage on weekdays.
There is a table that shows a carrier name and their load factors. There are many NaN values.
Load factor is shown by year, quarter, and month.

3. Flight Analysis (Dashboard 3):
The number of flights is analyzed by aircraft group and distance.
Jet aircraft with 2 engines are the most common.
Flights with less than 999 miles are the most common distance.
Top routes are identified based on the number of flights, with Chicago to Detroit and Washington DC to Charlotte being prominent.

4. Interactive Flight Search (Dashboard 4):
The dashboard includes interactive filters for origin and destination countries, states, and cities.
A table displays detailed flight information, including airline ID, name, code, month, day, day name, weekday/weekend, transported passengers, and available seats.
Hawaiian Airlines and Delta Airline are used as examples.
There is a map of the united states, and surrounding countries.

SQL Query:

Potential Further Analysis:
Detailed analysis of load factor variations across different routes and airlines.
Investigation of factors influencing passenger preferences.
Predictive modeling of flight delays or cancellations based on historical data.
Geospatial analysis of flight patterns and network optimization.
Analysis of the NaN values in the load factor table.
Analysis of monthly trends.


Tools used - Microsoft Excel, MySQL, Power BI
