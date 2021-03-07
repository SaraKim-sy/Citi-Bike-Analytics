# NYC Citi Bike Analytics

Find the completed NYC Citi Bike Analytics dashboard here: [NYC Citi Bike Analytics](https://public.tableau.com/profile/sooyeon.kim#!/vizhome/citi-bike-analytics_16150734273910/NYCCitiBikeAnalytics/)

## Overview
Citi Bike is the nation's largest bike share program, with 15,000 bikes and over 1,000 stations across Manhattan, Brooklyn, Queens, the Bronx and Jersy City. Find more information about the bike share program, visit the citi bike website, https://www.citibikenyc.com/

- - - 


## Citi Bike Analytics - Tableau Storyboard
This Storyboard is to analyze and visualize New York City Citi Bike Share program data. The purpose of this project is to answer the common questions users have, such as  'Which staions are most popular?', 'What days of the week are most rides take on?', 'How is the user demographics?', etc. The analytics used Citi bike data from January 2020 to December 2020.

![dashboard](./Resources/dashboard.gif)

## Analytics & Insights

- The 'User Demographics' dashboard shows that Male riders consist the most significant portion, followed by female riders. 'Unknown' category users are mostly from 'customers' other than subscribers. It seems that that's because subscribers have the gender information, while for the customers who purchased a 24-hour pass or three-day pass, there are less available gender data about the users. Plus, about two-thirds of users are subscribers.

- One noticeable thing from the 'bike Trips by Month/Gender' is that there was a significant drop in the number of users in April. The cause seems to be the covid 19 virus pandemic which started around March in 2020. Therefore this situation appears to affect the number of users significantly. 

- Looking at the 'trip duration by 'age', it seems that the younger age group between 18 and 40 are likely to have longer bike rides than the older age group. 

- 'Popular Ride Times Analysis' shows more bike riders on Weekends than weekdays. However, if we filter by the subscriber, it is noticeable that there are more bike riders on weekdays than weekends. From peak hours in winter graph, we can see that there are more bike riders around commuting hours; we can guess that many bike riders use the Citi-bike program to commute. Many of them seem to be subscribers of the program. On the other hand, seeing the peak hours in summer, the peak time for bike trips is between 5 pm and 7 pm. 

- We can see the most popular stations for starting a trip in the 'Start Stations Dashboard' and the most popular stations for ending a trip in the 'End Stations Dashboard'. You can explore the dashboard by filtering months. The top 10 start stations include Grove St Path, Newport Pkwy, Liberty Light Rail, Hamilton Park, and Sip Avenue. The top 10 end stations include Grove St Path, Newport Pkwy, Liberty Light Rail, Hamilton Park, and Marin Light Rail. 


## Data
This storyboard was created with the data available in https://www.citibikenyc.com/system-data


- - -

## Technologies
This project was created with:
* Python 3.8
* Jupyter Notebook
* Tableau
