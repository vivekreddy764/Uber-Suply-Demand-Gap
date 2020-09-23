# Uber-Suply-Demand-Gap

# Introduction
This data set is a masked data set which is similar to what data analysts at Uber handle. Solving this assignment will give you an idea about how problems are systematically solved using EDA and data visualisation. 

## Business Understanding
You may have some experience of travelling to and from the airport. Have you ever used Uber or any other cab service for this travel? Did you at any time face the problem of cancellation by the driver or non-availability of cars?

Well, if these are the problems faced by customers, these very issues also impact the business of Uber. If drivers cancel the request of riders or if cars are unavailable, Uber loses out on its revenue. Let’s hear more about such problems that Uber faces during its operations.
As an analyst, you decide to address the problem Uber is facing - driver cancellation and non-availability of cars leading to loss of potential revenue. 

# Business Objectives
The aim of analysis is to identify the root cause of the problem (i.e. cancellation and non-availability of cars) and recommend ways to improve the situation. As a result of your analysis, you should be able to present to the client the root cause(s) and possible hypotheses of the problem(s) and recommend ways to improve them.  

**There are six attributes associated with each request made by a customer:**

1.**Request id**: A unique identifier of the request
2.**Time of request**: The date and time at which the customer made the trip request
3.**Drop-off time**: The drop-off date and time, in case the trip was completed 
4.**Pick-up point**: The point from which the request was made
5.**Driver id**: The unique identification number of the driver
6.**Status of the request**: The final status of the trip, that can be either completed, cancelled by the driver or no cars available

In this project we are considering only **trips to and from** the airport.

# Results Obtained 


![Image of Uber](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.theverge.com%2F2014%2F2%2F27%2F5453932%2Fuber-driver-experience-los-angeles&psig=AOvVaw36o5CgUm0yYAdu7iQjouax&ust=1600940253170000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMil9a_9_usCFQAAAAAdAAAAABAD)

**From Airort pickup**:Reason behind this gap may occur in different formats like in evening time slot seems to be most problematic for pickup points as airport where the requests being No Cars Available. The reason seems to be that not enough cars are available to service the requests as cars might not be available at the airport due to the cars serving inside the city or may driver worry about the traffic during the evening hours because leaving time of employees.

**From City pickup**:According to the analysis, the morning time slot is most stumbling block where the requests are being cancelled. Most probably the requests are being cancelled by the drivers due to the morning rush as it being the office hours and seeing the destination as airport which would be too far, the driver would think to earn more for the shorter trips within the city and may worry about traffic that customer may or may not reach the airport in time may result in bad review.

**conclusion**
Based on the data analysis performed, following recommendation can be used by Uber to bridge the gap between supply and demand:
1.For bridging the demand supply gap from airport to city, making a permanent stand in the airport itself where the cabs will be available at all times and the incomplete requests can come down significantly.(based on budget plan) 2.Uber can give some insentives to the driver who will complete the trip from city to airport in the morning part. This might result the driver to not cancel the request from city to airport trips. 3.And also by creating a freelance site so that uber can assign a cab to the third party and can get the commission from the above trips in this no need of keeping cars stand in the airport 4.Last but sure solution to bring down the gap is to increase the numbers of cabs and connections with the third parties in its fleet.
