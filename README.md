# NYC_Airbub_Opendata_Vis
visualization of the New York City Airbub open data downloaded from kaggle.

**data description**
The data was downloaded from kaggle:https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data
I just copy the data description from the website

**Context**
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present more unique, personalized way of experiencing the world. This dataset describes the listing activity and metrics in NYC, NY for 2019.

**Content**
This data file includes all needed information to find out more about hosts, geographical availability, necessary metrics to make predictions and draw conclusions.

**Acknowledgements**
This public dataset is part of Airbnb, and the original source can be found on this website.

**Inspiration**(It's also what I want to explore, but I will use matplotlib, numpy and pandas instead of R.)
What can we learn about different hosts and areas?
What can we learn from predictions? (ex: locations, prices, reviews, etc)
Which hosts are the busiest and why?
Is there any noticeable difference of traffic among different areas and what could be the reason for it?


**description of the data**


           latitude     longitude         price  minimum_nights
count  48895.000000  48895.000000  48895.000000    48895.000000
mean      40.728949    -73.952170    152.720687        7.029962
std        0.054530      0.046157    240.154170       20.510550
min       40.499790    -74.244420      0.000000        1.000000
25%       40.690100    -73.983070     69.000000        1.000000
50%       40.723070    -73.955680    106.000000        3.000000
75%       40.763115    -73.936275    175.000000        5.000000
max       40.913060    -73.712990  10000.000000     1250.000000



**1.average price in every neighborhood group**

Firstly, I'd like to show the average price of the airbub in every neighborhood group.


![aveprive](https://github.com/jianght1999/NYC_Airbub_Opendata_Vis/assets/80138413/76c6dca2-0aba-4bd2-913f-14c4ece39575)
