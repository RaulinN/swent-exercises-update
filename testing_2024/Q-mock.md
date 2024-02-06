Supppose you are developing a service that recommends hikes near users based on the weather, 
and the module should take as input a weather service, a service that lists hikes,
a function that sorts hikes by length, and outputs an array of hikes.

How would you test the module and make sure it works under different weather conditions ? It's possible that new hikes are discovered and provided by the service in the future, how would you make sure the module is robust under hike changes ?