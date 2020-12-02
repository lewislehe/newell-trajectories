# newell-trajectories

A jupyter notebook that calculates and plots trajectories with instantaneous acceleration according to the newell car following model. You plot the trajectory of a "leader" vehicle and then it calcualates a number of "follower" vehicles' trajectories, given their initial positions. This is for making time-space diagrams to teach traffic flow theory, which can be a headache for lecturers.

Explained here:
https://en.wikipedia.org/wiki/Newell%27s_car-following_model 

Newell, G.F. (2002) "A simplified car-following theory: a lower order model" **Transportation Research Part B: Methodological** 36 (3), pp. 195-205. https://doi.org/10.1016/S0191-2615(00)00044-8

An issue with the presentation of the Newell model is that the original citation and all expositions of it only explain how to deal with trajectories in the "congested" ("hypercongested" in economics parlance) traffic regime. This program calculates even when conditions are uncongested. It uses numpy and matplotlib python libraries to do so.