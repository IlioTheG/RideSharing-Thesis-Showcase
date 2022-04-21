# RideSharing-Thesis-Showcase
___
The topic of my thesis was **taxi-sharing** and the benefits of applying it as a mode of transportation in the city of Thessaloniki in Greece. To do so, I implemented an algorithm in Python which out of a set of e-hail requests creates **pairs** of requests created in a 5 minutes time window that can share a ride. <br>
To create the pairs the algorithm considers multiple criteria i.e.:
1. maximum waiting time for the second passenger 
2. increase in time to serve a request comparing individual and shared trips for each one of the passengers.<br>

The algorithm ran on real world data provided by [Beat Taxi](https://thebeat.co/en/?intl=1), in different waiting-time scenarios and various tolerance in increasing total service time for the passengers. These scenarios were set under scope to evaluate matching rate - investigate how different parameters affect the number of pairs created in those scenarios - as well as the reduction in kilometers and total travel time - system wise - to serve the same number of requests. 
Apart from the algorithm, the requests analyzed temporally to identify time windows with higher demand as well as spatially to identify regions of the city which produce and attract more trips. <br><br>
Currently the [Notebook](https://github.com/IlioTheG/RideSharing-Thesis-Showcase/blob/main/Map%20demo.ipynb) hosts a map which depicts total trip requests in a specific time window (i.e. 08:00 - 08:05) and total pairs created in it. <br>
Original live Notebook includes an interactive slider to manually select desired time window which updates the map as shown in Fig.1. <br>
___



![img](/imgs/int_map.png)
*Fig.1 Interactive map* <br>
___

Original Thesis in Greek is available [here:notebook_with_decorative_cover:](http://ikee.lib.auth.gr/record/335719/files/HLIOPOYLOS804_DE.pdf)<br>
*Database with trip requests can not be shared*
