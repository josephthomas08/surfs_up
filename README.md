# surfs_up
## Improving surfing experience for clients  by analyzing data


## Overview:

The project in hand is with W. Avy who so far had a great expereince working with us and he has further instructed us to provide him with  more information about temperature trends before opening the surf shop. 

More Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.
The tools we have used to provide the detailed analytical report were:


Python(Pandas, Matplolib), SQLAlchemy. 
Flask was used to provide a preview but we have not used FLask for generating this report.

## Results:

The  weather data requested by Mr. Avy was specifically for the months of June and December. The charts below provides a detailed overview of the weather differences between these two months. The difference as we see is very minimal.

#### 1. The Rainfall difference is hardly 0.5 inches.
#### 2. Average rainfall for December is 2 inches higher than June.
#### 3.The temp difference as well is merely 2 deg.
#### 4.The low temp diff is a bit more that the higher ones but again it is only 8 degree diff.
#### 5.Average temperature is only 4 degrees different with June being the hottest.
from the above provided data we can deduce that Hawaii has terrific year-round weather.

### D1: Determine the Summary Statistics for June

<img width="276" alt="June_stats" src="https://user-images.githubusercontent.com/75267605/109105052-297f2780-76fb-11eb-98a4-e97d88cbcd05.png">

### D2: Determine the Summary Statistics for June

<img width="272" alt="December_stats" src="https://user-images.githubusercontent.com/75267605/109104851-c8575400-76fa-11eb-8653-57f6eaa7fad6.png">

### Further analysis 

#### June percipitation 
<img width="214" alt="June percp" src="https://user-images.githubusercontent.com/75267605/109177651-07ff5980-7756-11eb-893b-83d5a126b869.png">

#### December Percipitation 

<img width="180" alt="December percp" src="https://user-images.githubusercontent.com/75267605/109177825-3846f800-7756-11eb-8126-388690068c04.png">




## Summary:* 

The following analysis is further advised to Mr Avy before we open ths shop to better juddge and adopt the resources required over the low and high season of visitors.

#### 1. We will advice the management to let us expand the analysis to include all months of the year in order to visualize any seasonal differences , especially rainfall which can put a damper on ice consumption.
#### 2. It will be further a greate initiative to plot the rainfall data by month over the time-period in the database.
#### 3. lastly we should be engaging in other station analysis to other stations near possible locations for a second shop.
