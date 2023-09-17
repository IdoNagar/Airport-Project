# Airport-Project

<h2>Description</h2>
The project is about New-York airports.<br />
There are 5 csv files with some data about the New-York airports.<br />
In this Project I needed to analyze the data I got and the main focus was on delays and how to fix them.<br />
(The Data is already clean)
<br />


<h2>Languages and Utilities Used</h2>

- <b>SQL</b> 
- <b>Excel</b>

<h2>SQL codes:</h2>

<p align="center">
Created a new table named "DailyFlights" with 5 new column: </p>
<p align="left">
- Cancelled: based on dep_time which will get 1 if flight cancelled and 0 if not. <br />
- Date: new format in one column for year, month, day. <br />
- Delay Severity: to show if the delay was Easy, Medium or Hard. <br />
- Previous_dep_delay: showing the last delay for the same carrier (based on day, month, year, hour and minute). <br />
- plane_age: showing the plane age (relevant for the flight date). <br />
</p>
<p align="center">
<img src="https://i.imgur.com/LNjjKUX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
Created a new table named AllDailyData: <br/>
<img src="https://i.imgur.com/FmcWlRv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
Made a query for each month, by origin and carrier with new measures:
</p>
<p align="left">
- num_flights: shows the number of flights. <br />
- num_delayed_flight: shows the number of delayed flights. <br />
- num_of_cancelled_flights: shows the number of cancelled flights. <br />
- avg_dep: shows the average of delay by departure. <br />
- avg_arr: shows the average of delay by arrival. <br />
- num_of_destinations: shows the number of destinations. <br />
- prop_delayed_flights: shows the percentage of the delayed flights from total flights.

* I wanted to sum up the different levels of delay (between mild, moderate and severe), so I added this part here as well.
</p>
<p align="center">
<img src="https://i.imgur.com/EyJhR54.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
