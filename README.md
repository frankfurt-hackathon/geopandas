# geopandas
A hackathon to learn how to use geo pandas and based on kaggle competition data found in https://www.kaggle.com/c/nyc-taxi-trip-duration

# Goal
Create a function that - given two coordinates inside Manhattan - gives an estimate of a taxi journey time in seconds:

```
def function(coord1=(lat, lng), coord2=(lat, lng)):
    ...
    ...
    ...
    return est_journey_time
```

This function is better when it acheives a lower mean_squared_log_error using the evaluation set.
