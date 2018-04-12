## t-its2018


Please cite our paper journal if you publish material based on those datasets.
* Paper not yet published

## Dataset Description

We have used the datasets available in NYC and Tokyo Check-in Dataset available in [https://sites.google.com/site/yangdingqi/home/foursquare-dataset] to derive two others datasets in the context of ride-sharing mobility: 

(1) routes dataset. it contains the fastest path between the two most frequently visited venues for each user (Files: "routes_tky.json" and "routes_nyc.json"). <br>
(2) ride requests. it contains the representation of ride request specifying pickup location, intended destination and pick-up time.  

The whole dataset has been compressed for one-week time window.

### Routes dataset

Each line of the dataset contains a json with a key-tuple (user_id, venue_destination_id) and the following properties:

**path:** contains the metada regarding the trips such as user_id and the departure and destination venues (including their ids, latitude and longitude).

**google direction:** google direction api [developers.google.com/maps/documentation/directions/] route result. 

**schedule:** weekdays wich the destination was visited by the given user (e.g. 0 monday, 1 tuesday, and so on.) 
The time is computed considering the median among all the checkins datetime which the given user visit this destination. 


### Ride requests

Not yet available.



For further information, please contact us by email:

vcml@cin.ufpe.br
renso@isti.cnr.it
