Note: I wasn't able to add the files into GitHub as it told me it was too big c:

Link to Dashboard: https://public.tableau.com/app/profile/eduardo.aleman/viz/2020vs_2023/Covidvs_2023?publish=yes

When analyzing data, it's best to choose a consistent variable. That is why I chose the first month of the year in NYC as it's usually a time where people are open to start a new hobby and or get healthier. Not to mention in January, the temperature is cold which would deter some people from riding. 

I started in the year 2020 as there was a lot of uncertainty with COVID and want to analyze how ridership has changed throughout the years up to this year in 2023.

The data cleaning process was tedious as data from the year 2020 contained columns of data that was not present within data in the year 2023. Not to mention that there wasn't a column that I could have joined the year by as the year 2020 used BIkeID and 2023 used UserID.

So I had the idea to concatenate the two data frames by renaming column names as well as adjusting variable names for the sake of consistency. By doing so I decided to make 3 dashboards that will highlight data that is unique to those years as well as a joint dashboard that can give insights as to the shift in ridership or user types that have seen success. 

Dashboard 1 (2020 Focus)

The information I gained from this dashboard would be that men had much longer trip durations than women. Although it's clear to see from the stacked bar chart I believe that this can add value to city officials that can help fund marketing strategies towards women. 

I also found age to be very interesting in the stacked bar chart. At first I thought the data was going to be heavily skewed right as younger people are usually more active than those that are middle aged. Wrong, as those in their early to mid thirties and above are more active compared to those in their twenties. Just looking at the data, those that are in their 50’s to early 60’s are more active than those in their 20’s making city officials ask the question as to why the youth is lagging in physical activity.

As it's not only trip durations that are longer, but the percentage of users. For subscribers women make up less than a quarter, however for customers they are more than 25%. Meaning that Customers can be people coming to NYC on vacation and or first time riders that did not find the need to become a subscriber. I know this to be true as the number of subscribers far outweighs the number of customers meaning that people must have loved the service so much in order to find the need to subscribe.

However I believe that the map gives city officials an opportunity to see where the hot spots are for both women and men. I believe this to be important information as by looking at the intensity of the map. Optimizations can be made to better suit both men and women as well as seeing where intensity may be weak and have a further in depth analysis of possible crime or routes that deter riders from riding in certain areas.

Dashboard 2 (2023 Focus)

In 2023, CitiBike decided to remove columns, gender and age. I believe it to be a bad idea to remove those two columns as they can give way to an in depth analysis to see if age or gender dropped and or increased from 4 years prior to when the data was collected in the year 2020. 

However, CitiBike introduced the type of bike consumers were using when riding within the city. Both Classic and Electric bikes were an option and I wanted to see how they performed within the city of New York. 

My analysis would be that classic bikes blew electric bikes out of the water when comparing usage. I used User Type to differentiate user preference as I didn't have age or gender. From the stacked bar chart it’s clear to see that classic bikes had the most users and from the pie chart you can see that electric bikes don't make up a quarter of the chart.

I provided a map of the intensity of bikes used in order to give city officials an opportunity to see where electric bikes are mostly used. Possible charging stations for popular spots for eclectic riders as well as popular locations for those that prefer a classic bike. 

I will also add that additional data such as the number of electric bikes and classic bikes were available as I would be able to provide a better analysis on the popularity of the type of bike. It could be that there are far less electrical bike options but they are used multiple times, or it could be that there is an equal amount of each bike. To be honest we wouldn't know unless the data was provided. Maybe a BikeId column could have been added to see if a bike has been worn down from over usage, and or seeing if an electric bike could use a new battery. The amount of analysis that could be made could be valuable to a government official.


Dashboard 3 (2020 vs. 2023)

For the third dashboard I wanted to analyze both years in a single dashboard in order to see if there was a growth and or a change in trend. 

I started with the time of day that the bikes were used and it looks to be consistent to what a normal day would look like for those that might be commuting to work. As seen from the data it looks as if there are two peaks and the first is around the time that work would start around 8am and for those ending work around 5-6pm. 

As for the days in January there are days when ridership is slow. If I were to get data from the past 4 years I would be able to possibly see a trend of days that had zero to no ridership that can be attributed to a number of variables like weather and or event within the city that might prevent ridership. 

When measuring the number of increased users I decided to focus on the time of day that people start and end work. For the peak work hours at 8am. There were 110k users in the year 2020 and 116k in the year 2023. As for the end of the day around 5-6pm, 2020 had 112k users and 143k users in 2023. I would have wanted to see a greater increase as NewYork has a population of 8.5M people. 

Conclusion

If I had more time I would have wanted to create the average distance a user would go in order to understand what is the most and least amount of distance a person would go in order to use the service. 

I would also like to have information to see the average distance a commuter would take as it would give insights from the previous observation to see if taking a bike is worth it. Not to mention that NY has an amazing transit system so it could be that taking a bike could not be worth it.
