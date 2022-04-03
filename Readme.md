# Uber Supply-Demand Gap Analysis
## Problem:
The aim of analysis is to identify the root cause of the problem (i.e. cancellation and non-availability of cars) and recommend ways to improve the situation. As a result of your analysis, you should be able to present to the client the root cause(s) and possible hypotheses of the problem(s) and recommend ways to improve them.
## Dataset overview:
* There are 6745 rows and 6 columns.
* Columns as follows:
    * Request id: A unique identifier of the request
    * Time of request: The date and time at which the customer made the trip request
    * Drop-off time: The drop-off date and time, in case the trip was completed
    * Pick-up point: The point from which the request was made
    * Driver id: The unique identification number of the driver
    * Status of the request: The final status of the trip, that can be either completed, cancelled by the driver or no cars available.

## Hypothesis through analysis:
* **At city pickup point**: The morning time slot is most problematic where the requests are being cancelled. Most probably the requests are being cancelled by the drivers due to the morning rush as it being the office hours and seeing the destination as airport which would be too far, the driver would think to earn more for the shorter trips within the city.
* **At airport pickup point**: The evening time slot seems to be most problematic for pickup points as airport where the requests being No Cars Available. The reason seems to be that not enough cars are available to service the requests as cars might not be available at the airport due to the cars serving inside the city.

## Solution:
* For bridging the demand supply gap from airport to city, making a permanent stand in the airport itself where the cabs will be available at all times and the incomplete requests can come down significantly.
* Uber can provide some incentives to the driver who complete the trip from city to airport in the morning part. This might result the driver to not cancel the request from city to airport trips.