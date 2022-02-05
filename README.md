#  Overview of the analysis:

Kate and I had traveled for fun and and noticed how many individuals how many individuals used a bike sharing program for commuting.  Giving us the idea that we may be able to start a bike sharing company in our home city of Des Moines.   Kate was lucky enough to find an investor that could back the company, but we need to better understand how the system worked in NY to know if it's something we can do in Des Moines

#  Results:

Knowing that there are quite a few differences between New York and Des Moines, we dicided to look at a few key features, and visualized the data in Tableau.  Here's what we noticed about the trip data from NYC and how it could impact the usage in our town.

 - **Peak Hours in August**:  It's clear from the data that most usage of the bikes were used for commuting to and from work.  Also, when looking at the data (from August) it also shows a steady increase in usage throughout the aftternoon and a drop off in the evenings.   This likely indicates that not only are these bikes used for commutes, they are also likely used for afternoon errands, and in NY likely some afternoon sight seeing.

https://github.com/JohnJohnson913/bikesharing/blob/669f725ee4f79015927922c791ed6ec2577e3c16/peak_hours.png

- **Gender Usage**:  We also noticed a significantly larger grouping of men rent the bikes over women.  The average usage numbers by men are nearly 300% greater during peak useage and even greater during lesser desirable times.  This reinforces the fact that the compesition of gender in our user type is also nearly 3 to 1 men vs women.

https://github.com/JohnJohnson913/bikesharing/blob/669f725ee4f79015927922c791ed6ec2577e3c16/weeks_per_day.png
https://github.com/JohnJohnson913/bikesharing/blob/669f725ee4f79015927922c791ed6ec2577e3c16/subscribers_vs_custoemer_gender.png
https://github.com/JohnJohnson913/bikesharing/blob/669f725ee4f79015927922c791ed6ec2577e3c16/trips_by_gender.png

- **Subscriber vs Customer**:  Additionally we evaluated the subscriber based model and it's effectiveness when looking at usage.   Turns out subscribers greatly outnumber the volume of users from a customer or nonsubscriber base.  Getting users subscribed is key.

https://github.com/JohnJohnson913/bikesharing/blob/669f725ee4f79015927922c791ed6ec2577e3c16/subscriber_vs_customer.png

- **How long do individuals use the bikes?**:  This metric indicates that several users only use the bikes for only about 5-6 minutes a day.  Meaning that the trips that are taken are often only a short trip, likly in their own neighborhood.  This is key for our use case, as NYC and Des Moines have drastically different urban density.  

https://github.com/JohnJohnson913/bikesharing/blob/669f725ee4f79015927922c791ed6ec2577e3c16/check_out_times.png

- **Start and Stop Locations**:  Another metric that may help define success is also a geographical item, this would how far does each bike travel between it's start and stop location.  In a similar manner with the trip duration, we've found that often times the start and stop locations of rides is in very close proximity.  This reinforces the ride data on trip times.   Again likely due to density of NYC.  Also, noticed the usage in the urban core of NYC, and the drastic difference when compared to suburbs.  This will be key.

https://github.com/JohnJohnson913/bikesharing/blob/669f725ee4f79015927922c791ed6ec2577e3c16/start_stop.png

#  Summary:

In summary, this plan has the potential to be successful, however some major hurdles will need to be overcome to make this a vialble option in a city so drastically different that NYC.  I've included a few ideas to explore to help make this a success.

- **Consider scooters, not bikes**:  Due to such a difference in urban density our users are likely going to have to ride much greater distances to reach their destination, making bikes difficult choice to make.   Especially in suburban settings consider the use of electic scooters.  Users can use these with much more ease, they are just as fun and offer an easier way to travel.  We could easily complete a simliar analysis on the usage of scooters as compared to the usage of bikes.

- **Better safe....**:  Due to the two cities being compared is so different, I would recommend a similar comparison against cities similiar in characteristics.  I've heard Salt Lake City has started a similiar bike sharing program, we could explore their data and see how it's going there.   They have a similar climate, population and density, it may be a safer and more accurate comparison.
