# airline-sql-analysis
SQL and Tableau analysis of BTS T-100 international airline passenger data.
International Airline Carriers and Aircraft Types by Passenger – Analysis
Project Overview: 
This project analyzes international airline passenger traffic using the U.S. Department of Transportation Bureau of Transportation Statistics (BTS) T-100 International Segment dataset.
The goal was to demonstrate the ability to import data, perform SQL analysis, export results, and communicate findings through a dashboard.
--
Dataset
Source: Bureau of Transportation Statistics (BTS)
Dataset: T-100 International Segment
Time Period: 2025, monthly
Records: 111,914
Fields downloaded: Passengers, Freight, Distance, Carrier, Airline ID, Origin Airport, Destination Airport, Aircraft Type, Year, Month
Fields used: Passengers, Carrier, Aircraft type, Year, Month
Tools used: SQLite; DB Browser for SQLite; SQL; Tableau Public
--
SQL Techniques Demonstrated
SELECT – WHERE – GROUP BY – ORDER BY – LIMIT – HAVING – SUM() – COUNT(DISTINCT(…)) – Multi-field grouping – Data aggregation – Trend analysis – Ranking analysis
--
Analysis Performed
Monthly Passenger Trends: Analyzed international passenger volume by month to identify seasonal patterns.
Top Carriers by Passenger Volume: Ranked carriers based on total passenger traffic.
Top Aircraft Types by Passenger Volume: Compared passenger volumes across aircraft types. 
Aircraft Adoption vs. Passenger Volume: Compared the number of carriers operating each aircraft type against total passenger volume to evaluate utilization patterns.
Carrier-Aircraft Utilization: Examined carrier and aircraft combinations to identify operational concentration and usage patterns.
--
Dashboard components:
Monthly Passenger Trend – Top Carriers by Passenger Volume – Top Aircraft Types by Passenger Volume – Aircraft Adoption vs. Passenger Volume
--
Key Takeaways
-	International passenger volume exhibited clear seasonal trends.
-	Passenger volume was concentrated among a relatively small number of aircraft types.
-	Aircraft utilization varied between broadly adopted aircraft and aircraft used heavily by a smaller number of carriers.
-	SQL aggregation and grouping techniques were used to transform raw transportation data into dashboard-ready reporting outputs.
--
Skills demonstrated
-	Data import and validation
-	SQL querying and aggregation
-	Operational data analysis
-	Tableau dashboard development
-	Data visualization
-	Trend and utilization analysis
--
Project Purpose: This project was created as a part of a SQL portfolio focused on developing SQL skills.
