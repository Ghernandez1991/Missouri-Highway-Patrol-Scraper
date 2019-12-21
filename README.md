# Missouri-Highway-Patrol-Scraper


The purpose of this project is to build a webscraper to fetch and download data from the Missouri Highway Patrol accident website. 

Site: https://www.mshp.dps.missouri.gov/HP68/SearchAction



1- The app uses Splinter to automate the google chrome browers to visit the website and search for fatal accidents. 

2-THE CHALLENGE
The website uses javascript calls to query the data the user selects. This is constantly updated as new accidents come in. Additionally, there are some 588 auto accidents listed for the past calendar year. The time needed to click each link(588) and copy and paste the respective data would be immense. 

3-The application finds the xpath link and using a for loop, clicks thorough all the links. While inside the loop, we store the information in a list to manipulate later. 

4-After the webscraping is complete(~5 mins), we can manipulate the list of all fatal accidents with respective gps/location data. After some data cleaning, we are able to get the data into a dataframe and to a csv. The visualizations are created in Tableau and shared below.

Tableau Visualizations
https://public.tableau.com/profile/gabriel.hernandez8655#!/vizhome/MissouriHighwayPatrolFatalities/FatalitiesbyCounty-Map

https://public.tableau.com/profile/gabriel.hernandez8655#!/vizhome/MissouriHighwayPatrol2/InjuryTypesbySex








![Image description](https://github.com/Ghernandez1991/Missouri-Highway-Patrol-Scraper/blob/master/images/image.PNG)
