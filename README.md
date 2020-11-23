# Finding the Best Neighborhood in Pittsburgh
Final Project for CMPINF 0010

### Team Name: FLO
### Group Members:
+ Jackson Frank (jrf114@pitt.edu)
+ Erasto Omolo (eoo5@pitt.edu)
+ Daniel Lucash (dvl4@pitt.edu)



### Datasets Used

+ [Alleghany County Illegal Dumpsites Dataset](https://data.wprdc.org/dataset/allegheny-county-illegal-dump-sites)
    + All illegal dumpsites in the Pittsburgh area.
+ [City of Pittsburgh Trees](https://data.wprdc.org/dataset/city-trees)
    + All of the city-owned trees in Pittsburgh.
+ [Pittsburgh Census Information](https://pitt.libguides.com/pghcensus/pghcensustracts)
    + The Pittsburgh census information of Pittsburgh.
+ [Pittsburgh Particulate Matter](https://data.wprdc.org/dataset/particulate-matter-2-5)
    + A dataset containing all of the particulate matter in Pittsburgh.

Analysis:
Our group decided to find the best neighborhood by trying to find the cleanest/most environmentally friendly neighborhood. We accomplished this by looking at these specific metrics:

Illegal Dumpsites: the amount of illegal dumpsites in each neighborhood (picked the one with the least) East Libery and Springdale 
Trees: the amount of trees in each neighborhood(picked the neighborhoods that ranked in the top) Squirrel Hill North
Particulate Matter: a measurement of air particulates/pollution in each neighborhood (picked the neighborhoods that had the least. Chartiers City Upper Lawrenceville	

We concluded this by ranking each neighborhood for each metric (based of its position), adding those rankings up, and seeing who had the smallest sum. We excluded neighborhoods who didn't appear in all of the metrics

Highland Park and East Liberty are the cleanest neighborhoods in Pittsburgh according to our matric.
