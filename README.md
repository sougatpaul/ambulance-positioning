# Uber-Nairobi-Ambulance-Perambulation-Challenge

## Objectives 
This objective of this challenge is to create an optimised ambulance deployment strategy in Nairobi using Machine Learning, using historical information of past accident locations. 

We are permitted to move the placements of the 6 virtual ambulence locations every 3 Hours to minimise the distance between the accidents in the test set and the location of the nearest ambulence. 

## Experiments Carried Out to Date

### 1. Using different clustering techniques using only past incident location data. 

The hypothesis was that accidents occur in similar patterns over time, such as some areas generally have more accidents than others (hotspots). To capture some of the latent information that may affect road accidents (such as Seasons, Weather etc), we applied KNN algorithm for each month to determine static locations for each Month.

See Notebook: Uber_Nairobi_Ambulance_Challenge_Clustering_Approach.ipynb


## References
For more information on thhis challenge or to access the data please refer to this website: https://zindi.africa/competitions/uber-nairobi-ambulance-perambulation-challenge


