# Predict Flight Delays
 Predict flight delays by creating a machine learning model in Python 
 
 
![giphy](https://user-images.githubusercontent.com/65978629/84071338-e5e56180-a9a3-11ea-8e65-bbe09bc0ba8d.gif)

In this model I used a classification model to predict whether a flight will arrive on time or delayed.

 ## **Column Description**

<ul>
<li><b>YEAR</b> - Year that the flight took place</li> 
<li><b>QUARTER</b>	- Quarter that the flight took place (1-4)</li>
<li><b>MONTH</b> - Month that the flight took place (1-12)</li>
<li><b>DAY_OF_MONTH</b> - Day of the month that the flight took place (1-31)</li>
<li><b>DAY_OF_WEEK</b>	- Day of the week that the flight took place (1=Monday, 2=Tuesday, etc.)</li>
<li><b>UNIQUE_CARRIER</b> - Airline carrier code (e.g., DL)</li>
<li><b>TAIL_NUM</b> - Aircraft tail number</li>
<li><b>FL_NUM</b> - Flight number</li>
<li><b>ORIGIN_AIRPORT_ID</b> - ID of the airport of origin</li>
<li><b>ORIGIN</b> - Origin airport code (ATL, DFW, SEA, etc.)</li>
<li><b>DEST_AIRPORT_ID</b> - ID of the destination airport</li>
<li><b>DEST</b> - Destination airport code (ATL, DFW, SEA, etc.)</li>
<li><b>CRS_DEP_TIME</b> - Scheduled departure time</li>
<li><b>DEP_TIME</b> - Actual departure time</li>
<li><b>DEP_DELAY</b> - Number of minutes departure was delayed</li>
<li><b>DEP_DEL15</b> - 0=Departure delayed less than 15 minutes, 1=Departure delayed 15 minutes or more</li>
<li><b>CRS_ARR_TIME</b> - Scheduled arrival time</li>
<li><b>ARR_TIME</b> - Actual arrival time</li>
<li><b>ARR_DELAY</b> - Number of minutes flight arrived late</li>
<li><b>ARR_DEL15</b> -  0=Arrived less than 15 minutes late, 1=Arrived 15 minutes or more late</li>
<li><b>CANCELLED</b> - 0=Flight was not cancelled, 1=Flight was cancelled</li>
<li><b>DIVERTED</b> - 0=Flight was not diverted, 1=Flight was diverted</li>
<li><b>CRS_ELAPSED_TIME</b> - Scheduled flight time in minutes</li>
<li><b>ACTUAL_ELAPSED_TIME</b> - Actual flight time in minutes</li>
<li><b>DISTANCE</b> - Distance traveled in miles</li> </ul>

This notebook was made based on [this training](https://docs.microsoft.com/en-us/learn/modules/predict-flight-delays-with-python/).
