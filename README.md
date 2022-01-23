# associate-datapoints-to-a-graph
This repository contains a notebook, that demonstrates an efficient approach to calculating the nearest road to each of datapoint in a given dataset, 
and further speeding up the code with numba.

I generated a 1k points in London city centre

![image](https://user-images.githubusercontent.com/76249196/150677057-cdece03f-91ff-4467-9bf0-a6d5f8622d7f.png)

Than calculated the nearest street for each point. with numba speed-up and without it. 
The calculation took the following times:

- without numba  -  4 minutes, 27 seconds
- with numba  -  0 minutes, 3.4 seconds

Sanity check. Here is an exemple of a streen and points? associated with it.

![image](https://user-images.githubusercontent.com/76249196/150677139-07563924-6a5a-4482-9a1e-eeea6fddad3f.png)
