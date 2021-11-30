# PSN
ALS PSN
Code was written using Python 3.
In the first lines all the needed packages are imported.

First part of the code is preprocessing: creation of three datasets, selecting 3 subsets of features.
Secondly, a function which computes similarity measures given a dataset and two nodes is presented.
Finally for every dataset are constructed 9 networks: for different thresholds values a network is constructed consider only one similarity measure at time.
In all the cases an edge is created if the specific similarity measure is higher then the current threshold.

The plots of each network and their metrics are given as output of the code.
