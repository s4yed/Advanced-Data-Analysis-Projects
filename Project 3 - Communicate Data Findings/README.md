# Ford GoBike System Data Exploration
## by Ahmed Sayed


## Dataset

Bay Area Motivate, LLC ("Motivate") operates the Bay Wheels bicycle sharing service. Motivate is committed to supporting bicycling as an alternative transportation option. And this document explores a dataset of Bay Wheels's trip on August 2019 rides.

The data consisted of duration in seconds and other time/location features of approximately **210,600** rides. The variables included the starting and ending time/locations of each ride.

In the wrangling process, I extracted some features from the existing variables such as `hours`, `days` of each ride, the euclidean `distance` from the given coordinates, as well as converted the `duration` time from seconds to minutes.


## Summary of Findings

The following results have been explored between the features in the dataset:

- Almost **90%** of the rides duration are below 23 minutes, while **97%** are below 38 minutes. 
- The bikes are generally used for short trips 1.5 km.
- The bike share system is busiest during commute hours and the workdays, as well as the quitest times are in the night early hours. 
- The majority of the rides are made by the subscribers with **78.3%** while the rest of the rides come from customers.
- A positive weak relationship has been observed between the two duration in minutes and the distance `r = 0.15`.
- Thursday and Saturday is the days that has most rides by subscribers and customers respectively.
- The customers' rides have made more on Saturday and Sunday.
- A user can travel by bike 1 kilometer in 2 minutes on average.
- All users use the bikes to do some cycling in the morning hours.


## Key Insights for Presentation

The following threads have been selceted to polish up:

- The distribution of the duration in minutes.
- Bikes Usage per hour.
- The distance traveled by users.
- The logarithmic duration by distance over all days.


## Resources
- [Jupyter Nbconvert](https://towardsdatascience.com/jump-out-of-the-jupyter-notebook-with-nbconvert-7d4748960702)
- [Data Visualization](https://towardsdatascience.com/complete-guide-to-data-visualization-with-python-2dd74df12b5e)