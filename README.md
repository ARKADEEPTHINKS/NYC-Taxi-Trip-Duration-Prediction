# NYC-Taxi-Trip-Duration-Prediction

DATASET: https://drive.google.com/drive/folders/1yqDs5HxZSFVtPjUAaQ3ey7Y8c9P6K2i9?usp=sharing


Problem Statement


At some point or the other almost each one of us has used an Ola or Uber for taking a ride.

Ride hailing services are services that use online-enabled platforms to connect between passengers and local drivers using their personal vehicles. In most cases they are a comfortable method for door-to-door transport. Usually they are cheaper than using licensed taxicabs. Examples of ride hailing services include Uber and Lyft.

To improve the efficiency of taxi dispatching systems for such services, it is important to be able to predict how long a driver will have his taxi occupied. If a dispatcher knew approximately when a taxi driver would be ending their current ride, they would be better able to identify which driver to assign to each pickup request.

Build a model that predicts the total ride duration of taxi trips in New York City.


Data Description:

id - a unique identifier for each trip


vendor_id - a code indicating the provider associated with the trip record


pickup_datetime - date and time when the meter was engaged


dropoff_datetime - date and time when the meter was disengaged


passenger_count - the number of passengers in the vehicle (driver entered value)


pickup_longitude - the longitude where the meter was engaged


pickup_latitude - the latitude where the meter was engaged


dropoff_longitude - the longitude where the meter was disengaged


dropoff_latitude - the latitude where the meter was disengaged


store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server (Y=store and forward; N=not a store and forward trip)


trip_duration - (target) duration of the trip in seconds
