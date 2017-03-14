# Boris Bikes Challenge  
  
This program will emulate all the docking stations, bikes and infrastructure of the London's Boris Bikes system.

### User story 1

Objects | Messages
------- | --------
Person |  
Docking station | check_docking_station
Bike | release_bike


### User story 2

Objects | Messages
------- | --------
Person |  
Bike | bike_status

### Combined stories

Objects | Messages
------- | --------
Person |  
Docking Station | bike_status
Bike | release_bike

###Diagram of interactions

```
Person --> bike_status --> true/false?
release_bike <-- if bike_status is true
```
