# Multiplex-Box-Office-Performance-Dashboard
The Multiplex Box Office Performance Dashboard provides a comprehensive overview of key performance indicators across multiple cinema locations. It tracks movie-wise revenue generation, footfall trends, occupancy rates, screen utilization, and performance
This dashboard visualizes and analyzes the box office performance of movie titles across multiple multiplex locations, helping stakeholders make informed decisions based on real-time and historical data.

Key KPIs (Main Metrics) : 
KPI Name	                     Formula / Basis	                            Insight it Gives
Total Cinema		           Count of unique Cinemas	  	           How many cinemas are listed
Total Movies		           Count of unique Movies	   	           How many Movies are running or schedules
Total Languages		           Count of unique Languages    	           Movies with actual Languages
Avg Occupancy Rate		           Average of Occupancy Rate               occupancy as per the Admits
Total Admit		           Sum of total Admits	           	           booking Tickets
Total GBOC		           Sum of total GBOC	           	           Gross Box Office Collections
Total NBOC		           Sum of total NBOC		                   Net Box Office Collections
Total Seats		           Sum of Total Seats available for booking	   Open booking Tickets

Visuals for Dashboard :
Visual Type	          What to Show	                        Based On  
Stacked Column Chart	Top 10 Movies as per Admits	        Movies and Sum of Admits
Stacked Bar Chart	TOP 10 Cinema as per GBOC & NBOC	Cinema, Sum of GBOC/NBOC
Gauge Chart	        Admits by Total Tickets	                Admits by Total Tickets
Pie Chart	        GBOC by Film Language	                GBOC, Film Language
Area Chart	        Day to Day Admit Analysis	        Date by date, Sum of Admits

Measures Needed for KPIs : 
KPI Name	           Measure Needed	                      DAX Example
Total Cinema	           Count of unique Cinemas	           m_Total_Cinemas = DISTINCTCOUNT('Table'[Cinema_Name])
Total Movies	           Count of unique Movies	           m_Total_Movie = DISTINCTCOUNT('Table'[FIlmName])
Total Languages	           Count of unique Languages	           m_Total_Languages = DISTINCTCOUNT('Table'[FilmLanguage])
Avg Occupancy Rate	   Average of Occupancy Rate	           m_Avg_Occupancy = AVERAGE('Table'[Occupancy_Rate])
Total Admit	           Sum of total Admits	                   m_Total_Admits = SUM('Table'[Admits])
Total GBOC	           Sum of total GBOC	                   m_Total_GBOC = SUM('Table'[GBOC])
Total NBOC	           Sum of total NBOC	                   m_Total_NBOC = SUM('Table'[NBOC])
Total Seats	          Sum of Total Seats available for booking	Sum_of_Total_Seats = sum('Table'[Total_Seats]) 
Note	"m"   (Represents Measure)
![image](https://github.com/user-attachments/assets/13bccac5-65df-471c-bc35-1078c6147b9e)

Advanced Insights : 
FILTERS/BUTTONS/NAVIGATION		 Filter Needed
Cinema Wise				To show the Insights according with 'Cinema Wise' Filter (More Granular)
Movie Wise				To show the Deep Insights according with 'Movie Wise' Filter (More Granular)
Date Wise				To show the Deep Insights according with 'Date Wise' Filter (More Granular)
Film Code				Deep Insights according with Film 'Code Filter' (More Granular)
Language				Deep Insights according with Film 'Language Filter' (More Granular)
Clear All Filters(Button)	        Button for clear all Filters (Back to Home)
![MULTIPLEX BOX OFFICE PERFORMANCE DASHBOARD 2025 NEW](https://github.com/user-attachments/assets/f6c6ecb4-d1ba-4a71-bcd3-76aa696f79fe)

✅ Key Features
Title-wise Revenue Analysis: Track gross/net collections by movie.
Location-wise Performance: Compare collections across cinemas/cities.
Occupancy & Footfall Trends: Analyze daily/weekly occupancy and audience turnout.
Format-based Analysis: Separate metrics for 2D, 3D, IMAX, etc.
Top Performing Titles: Identify high-performing movies by revenue and footfall.
Release Week Trends: Understand how titles perform over their theatrical run.
Weekend vs Weekday Comparison: Evaluate performance patterns.

🛠️ Data Sources
POS data from multiplex ticketing systems
Show-level and title-level box office reports
Daily occupancy and footfall data

📌 Usage Instructions
Use filters to view data by location, format, date range, or movie title.
Hover over charts for detailed tooltips.
Export functionality enabled for PDF and Excel snapshots (if applicable).

🎯 Target Users
Operations & Programming Teams
Marketing and Revenue Management
Regional Managers and Cinema Heads
Studio Partners and Content Acquisition Teams

🔄 Update Frequency
Dashboard updates daily (or specify refresh cycle: hourly, real-time, etc.)

The supporting files are attached on the project. 

Thanks for being a part of the project.
🚩🚩🚩🚩🚩Jai Shree Ram 🚩🚩🚩🚩🚩
