Strava Project
-------------

Strava project is a python data analysis performed to understand key questions we had below from the San Francisco Marathon race of 2017. 
To answer below key questions, we used techniques such as data scraping, data cleansing, and data visualization using python programing language.

Key questions are:
1) What does the Strava user population look like compared to overall marathon runners?
2) How did the Strava users perform at the race day compared to overall marathon runners?
3) How did Top20 Strava users perform on the race day ?
4) What can we do to race for better performance?

Jupyter notebook file
-------------------------------------------------------------
1) SFmarathon2017-Final.ipynb

We analyze strava user performance in the SF2017 Marathon.   
Jupyter notebook file is used to scrape San Francisco Marathon Official Result of 2017. 
Then, format the data to create the dataframe. Extract the dataframe tables into 2 csv files that will be used as the data input to merged strava and SF marathon jupyter file.






2) Strava_SF2017_Finishtime.ipynb

Jupyter notebook file is used to scrape Strava data of San Francisco marathon 2017 results. 
Then, format the data to create the dataframe. Extract the dataframe tables into 2 csv files that will be used as the data input to merged strava and SF marathon jupyter file.




3) Merged Strava and SFmarathon-Final.ipynb
This file was used to answer to the question "What does the Strava user population look like compared to overall marathon runners?" and "How did the Strava users perform at the race day compared to overall marathon runners?"


Imports csv files extracted from SFmarathon2017-Final and Strava_SF2017_Finishtime to plot both data to analyze the Strava user performance and Strava user demographics. Also calculate the mean and standard deviation to understand the spread of Strava user data.

![strava%20vs%20race.png](https://github.com/EmilySakata/Strava_project/blob/master/images/strava%20vs%20race.png)


Used the merged data to find the Strave user demographics.

![total_compete](https://github.com/EmilySakata/Strava_project/blob/master/images/total_compete.png)

4) Strava_Top20.ipynb
Description:
This file was used to answer "How did Top20 Strava users perform on the race day ?" and "What can we do to race for better performance?"

![top20runners](https://github.com/EmilySakata/Strava_project/blob/master/images/Top20runner.png)

Gathered top 20 user data from strava and plotted average pace per mile.




Detailed Summary observation of the data analysis can be found in Google Slides at the below link
Link to the Slides: https://docs.google.com/presentation/d/13T7g8kIl3w5cETWUAfhTE3sSMfebGHH1EcNHgxKQYEw/edit?usp=sharing



-------------------------------------------------------------
Contributors:

Daniel Saw      | https://github.com/dsdata1

Emily Sakata    | https://github.com/EmilySakata

-------------------------------------------------------------

Technologies Used:

-Python

-CSV


