# GreenRoute: A Fuel-saving routing system

Our current website to try:

http://greengps.cs.illinois.edu/html/green.html

We developed a fuel consumption model and calculated the estimated fuel on every road available in OSM map data. The routing result is for an averaged/normal car.
Our green routes are shown as green lines in Google Maps UI, Google's routes are shown in blue. 

Green routes may come slower, and our system only supports intra-state routing in some processed states for now. Sometimes green routes look like segments, lacking shape, this is because some geo-points' locations are missing in cache on our servers, it will look better once the cache system is warmed up. 

Currently processed states:
```
Illinois
Indiana
New York City
```

If you have requests of service for new regions, please email zhao97@illinois.edu