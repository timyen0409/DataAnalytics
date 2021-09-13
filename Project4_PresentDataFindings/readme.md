# Ford GoBike System Data

## by Chia-Hung Yen


## Dataset

This data is from lyft bikes that contains the information about the bike-sharing system covering the greater San Francisco Bay area. With 1863,721 bike rental records in 2018 with 14 features. This dataset include id, time, name and location of stations, bike id for each rental, and also the type of user whether they are enrolled in the Bike Share for All program. The dataset can be found on the lyft bikes website [here](https://www.lyft.com/bikes/bay-wheels/system-data)


## Summary of Findings

During the exploration, I found that there was a strong relationship between the day of the week with the trip counts. 
Also, I found that most of the subscribers should be commuters since the trips they made mostly were during rush hours. However, non subscribers were usually made trips during the afternoon of holidays. Besdie theprevious finding, the month of year also has influence on the trip counts, the peak months are from May to October, which happens to be the dry season of San Francisco. Therefore, we might be able to say that weather has a strong relationship with the trip counts. When I looed through the difference of the day of the week in each month separated by the user type, the results once again prove the conclusions I made from the previous findings are correct.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the user types and day of the week, then leave out most of the intermediate derivations. I start by showing the distribution of trips for each week of the day, followed by the distribution of each month in 2018. Afterwards, I show the trip counts of the hour for each day by each types of user with bar plot. Then, I finished the presentation with two heatmaps that demonstrate the distribution of trip counts on everyday in 2018 for two types of user.