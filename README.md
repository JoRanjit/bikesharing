# New York City Bike Trips

## This project is to analyze the pros and cons of 'New York Citybike Rental Program' to present it as a proposal in front of investors from Des Moines, Iowa. 
## If the investors are convinced of the feasibility of this proposal, they will invest on a similar program in Des Moines.

 #### * The bike trip data is downloaded from   www .citibikenyc.com-> Citi Bike trip data -> 201908-citibike-tripdata.csv.zip.
  #### * Python is used to clean-up this downloaded data.
 ![Dataframe]( https://github.com/JoRanjit/bikesharing/blob/main/Images/citibike%20dataframe.PNG)
 
 #### * Tableau is used to create an interactive presentation in the the form of Dashboards and Stories.
 
 Click here to view the interactive presentation in Tableau -> [Link to the NYC Citibike Dashboards]( https://public.tableau.com/app/profile/jo.ranjit/viz/NYCStory_16275135912480/NYCStory?publish=yes) 
 
 ###### First dashboard - New York City Bike Trips Info has the follwing tables and charts : <br>
      -- Total number of trips from August 2019 bike rentals. 
          (About 2 million trips in total - most of these riders could be visitors/tourists).
      -- Interactive pie-chart to breakdown the ridership by gender. 
          (About 40% of the total riderships are Male - which means more men-specific bikes are needed).
      -- Top starting locations
          (About 16k trips started from a particular spot in Manhattan - which means popular tourist spots may get more riders than others).
![dasboard#1]( https://github.com/JoRanjit/bikesharing/blob/main/Images/NYCStory_general_dashboard.PNG)

###### Second dashboard - NYC City Bike check-out times has 2 charts based on the check-out times in a day : <Br>
  
        --  Early morning check-outs peaks at the 1st 20 min, and then slowly flattens out.
              (About 150k riders rented early in the morning)
        --  Early morning check-outs are mostly done by male riders. Dashboard has menu options to analyse the trend by 'GENDER'.
              (about 100k + riders are men compared to women).)
  ![dashboard#2]( https://github.com/JoRanjit/bikesharing/blob/main/Images/NYCStory_checkout_dashboard.png)
  
  ###### Third dashboard - studies the trips by weekdays - with 'GENDER' options to choose from: <br>
  
      -- Weekend rides are pretty consistent through-out the day.
              (10:00 AM to 5:00PM saw the most rides in both weekends. In general 5:00 PM to 6:00 PM seems to be the most preferred riding times during weekdays).
              (Proposal should include plans to make sure that these peak hours are well stocked and supported.)
      -- The time preferences remain the same between men and women, but as we have seen earlier, there are more male riders than female.
  ![dashboard#3]( https://github.com/JoRanjit/bikesharing/blob/main/Images/NYCStory_Weekdaytrips_dashboard.png)
  
  ###### Fourth Dashboard - studies the impact of adopting a subscriber model: <br>
      -- Chart shows the ridership based on 3 categories: <br>
        * User type - New customer or a regular subscriber. (Chart has options to choose between these types)
        * Weekdays of the trips
        * Gender of the rider (Chart has options to toggle between the genders).
          Chart shows that the Subscriber users are more regular users than the non-subscirbers. Des Moines program should promote the Subscription model bike renting.
  ![dashboard#4]( https://github.com/JoRanjit/bikesharing/blob/main/Images/NYCStory_usertrips_dashboard.png)
  
  ###### Fifth dashboard - has some general miscellaneous information about the data set used: <br>
      -- 'August Peak Hours' chart shows that the bike riders start their trip as early as 12:00 am in the morning, peaking between 5:00-6:00 pm.
      -- 'Bike repairs' chart shows the bikes which have been driven the most and which are in a need of service.
          (A single bike could go upto 475+ rides in peak seasons. Des Moines should invest in good quality bikes to withstand this traffic).
  ![dashboard#5]( https://github.com/JoRanjit/bikesharing/blob/main/Images/NYCStory_misc_dashboard.png) 

 ### Additional suggestions for future visualizations apart from the pricing of the rides: 
 1. Create a chart on the preferred destinations which would show how many rides started from multiple locations but ended in the popular destiantions.
 2. Create a chart on the distance the riders are willing to ride to reach their detsinations,ie, how far the riders are willing to ride to reach their favorite destination.
