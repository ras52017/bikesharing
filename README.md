#**Citi Bike Sharing**
----------------------
[link to my dashboard] https://public.tableau.com/app/profile/erasmus.quaye/viz/TableauModule15BikeSharing/NYCStory?publish=yes

##**Overview: Analysis of Citi Bike data from New York City and it's application to Des Moines.**
-----------------------------------------------------------------------------------------------------
**After creating the analysis for New York City bike trip for all riders, I need to create a bike trip analysis for one of the key investors to convince him that a bike-sharing program in Des Moines is a solid business proposal.**

##**Analysis**
--------------

To start this analysis, I needed to understand the 5W's so I can tailor my analysis to the investor. I also needed to explain the advantages and disadvantages of introducing the bikesharing program in Des Moines. I used Pandas to transform sections of the provided data to a suitable datatype and used the converted datatype to create a set of visualizations. These visualizations is to provide the following information:

1. Show the length of time that bikes are checked out for all riders and genders  
1. Show the number of bike trips for all riders and genders for each hour of each day of the week  
1. Show the number of bike trips for each type of user and gender for each day of the week.  
1. Finally, I added these new visualizations to two others created in the module for presentation and analysis to pitch to the investors.  

##**The deliverables of this analysis are:**
- Change Trip Duration to a Datetime Format
- Create Visualizations for the Trip Analysis
- Create a Story and Report for the Final Presentation

##**Results:**

**1. This visualization shows the checkout time by user and gender. The results indicates that male users are the most dominant and the peak length of time for which bicks are checkedout is within the first 5 mins and starts to decline afterwards.**

![image](https://github.com/ras52017/bikesharing/blob/main/images/Checkout%20Times%20for%20Users.jpg)

![image](https://github.com/ras52017/bikesharing/blob/main/images/Checkout%20Times%20by%20Gender.jpg)


**2. This visualization shows the trips by gender weekday per hour and trips by gender by usertype where the usertype is categorized by customers and customers who are subscribers. It also showed that the male customers have more subscribers indicating that most of the males most often take trips than the female subscribers to work. Wednesday shows to be the less used days for both subscribers and thursday is the highest. 6 - 9 AM and 4 - 7 PM is the heaviest usage period.**


![image](https://github.com/ras52017/bikesharing/blob/main/images/Trips%20by%20Gender%20(Weekday%20per%20Hour).jpg)

![image](https://github.com/ras52017/bikesharing/blob/main/images/Trips%20by%20Gender%20by%20Weekday%20viz.jpg)

**3. This visualization shows the August peak hours and the top ending location. The visualization indicates that the Manhatan areas is the top ending location and the peak hours in the month of August is between 6 - 9 AM and 4 - 7 PM. The peak hours gives us information so that the investors will know when bikes must be available and slso the ending location can help us identify where to locate repair shops.**

![image](https://github.com/ras52017/bikesharing/blob/main/images/August%20Peak%20Hours.jpg)

![image](https://github.com/ras52017/bikesharing/blob/main/images/Top%20Ending%20Location.jpg)

**4. This final visualization tells the whole story of what is happening with the NYC bike sharing.**

https://public.tableau.com/app/profile/erasmus.quaye/viz/TableauModule15BikeSharing/NYCStory?publish=yes

##**Conclusion**
----------------
- It will be interesting to identify the cultural differences amongst the residents of Des Moines and NYC to identify if the Des Moines will be open to the use of the bike sharing. Also what conditions make it possible for the bike sharing to trive in NYC and see if that conditions are present in Des Moines. The bike sharing is loved by both male and females but the males patronises it the more.

##**References**
----------------
- Tableau, Python, Pandas
- The New York Citi data source was pulled from https://s3.amazonaws.com/tripdata/index.html using the  "201908-citibike-tripdata.csv.zip" zip file
- New York Citibike trip data: https://ride.citibikenyc.com/system-data

