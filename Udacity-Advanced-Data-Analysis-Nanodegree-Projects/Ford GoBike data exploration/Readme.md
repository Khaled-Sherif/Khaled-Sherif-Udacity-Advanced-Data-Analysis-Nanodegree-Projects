## Dataset

The data is about a bike rental app and consists of around 3000000 rows each  has 21 variables about a trip made using the service the features, include coords, duration, time of the trip, other info about the trip and some feaures that we added for exploration purposes. The dataset can be found on kaggale [here](https://github.com/tidyverse/ggplot2/blob/master/data-raw/diamonds.csv),
with feature documentation available [here](https://www.kaggle.com/victorinoeng/fordgobike20172019).

## Summary of Findings

In the exploration, we had to do some cleaning and adjusting to the data so the distributions of some variables look clear and representative.
Remarkable insights:
1) Distance column was extracted from the coords for each trip, season column was derived from the month column.
2) The distribution of all numeric features(duration_min, user_age, distance) are all left-skewed as it is expected with such type of data.
3) The daily peak of the trips occurs 2 times daily the first is between 7 and 9 am, and the second time is between 4 and 7 pm daily.
4) The count of trips per day during the week is the same except during weekend days(Saturday and Sunday) as the count is significantly less than the rest of the week.
5)The use of the service reaches its peak in March and April during the year.
6) Trips of people at age of 80 and 81 has avg duration higher than the rest.
7) of Variance in avg duration of Trips of people below 67 is less than people above than that age.
8)The duration of the trips between July and September is significantly higher than the rest of the year.
9)Trips made by males have longer distances and less duration.

We found that there is a relationship between the variables of interest and features like user_age, gender, time period.

## Key Insights for Presentation

The analysis showed a significant behaviour differences between genders in using the service and in riding bikes in general.
Males were much faster than females in reaching thier destination although their trips were longer regarding distance.
Most of the trips are usually between 5 and 15 minutes.
peak occurs 2 times daily the first is between 7 and 9 o'clock, and the second time is between 4 and 7 daily. 
Spring has the highest number of trips with a slight difference than the other 3 seasons. 
