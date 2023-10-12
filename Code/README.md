# Airport-Project

<h2>SQL codes:</h2>

<p align="center">
Created a new table named "DailyFlights" with 5 new columns: </p>
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
<br />

<p align="center">
Created a new table named AllDailyData: <br/>
<img src="https://i.imgur.com/FmcWlRv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
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
<br />

<br />
<p align="left">
- Changed the "dep_time" to an "hour format" <br/>
- Added new column that shows whether it's a good weather or bad weather <br/>
</p>
<p align="center">
<img src="https://i.imgur.com/2W2RfIy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/J1doLap.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
</p>

<p align="left">
In those next 2 codes I showed the sum of delayed flights and their percentage by good/bad weather: <br/>
- The first code is for the good weather <br/>
- The second is for the bad weather <br/>
</p>
<p align="center">
<img src="https://i.imgur.com/fXhqdcT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/LKqydyA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

Now I made more manipulations to try to understand more about the delayed flights:
</p>

<p align="left">
In the next query I found the flights that got delayed by destination<br/>
(only if there are more than 50 flights to those destinations): <br/>
</p>
<p align="center">
<img src="https://i.imgur.com/wcaFFuD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
</p>

<p align="left">
In this query I found the flights that got delayed by hour: <br/>
- 07-11 is Morning <br/>
- 12-16 is Noon <br/>
- 17-23 is Afternoob <br/>
- 00-06 is Night <br/>
</p>
<p align="center">
<img src="https://i.imgur.com/RFG30aN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />
<br />

<p align="left">
In this query I found the flights that got delayed by carrier: <br/>
</p>
<p align="center">
<img src="https://i.imgur.com/0HbBsWF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />

<p align="left">
In this query I found the sum of flights by plane age <br/>
</p>
<p align="center">
<img src="https://i.imgur.com/WPluj65.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
