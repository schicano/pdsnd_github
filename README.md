### Date created
November 22, 2020

### Project Title
Explore US Bikeshare Data

### Description
Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.

Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

### Files used
In this project, I will use data provided by Motivate, a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. I will compare the system usage between three large cities: Chicago, New York City, and Washington, DC.

* chicago.csv
* new_york_city.csv
* washington.csv

### Questions answered

The user is first prompted with a message:
Hello! Let's explore some US bikeshare data!

then, the user needs to respond the following questions:
* What city do you want to investigate?
* What month?
* What day of the week?

Once the user has chosen city, month and day of the week the following data is calculated and displayed based on those choices. It also displays how long the calculation took place.

1. Statistics on the most frequent times of travel

Calculating The Most Frequent Times of Travel...

The most popular month is...
The most popular day is...
The most popular hour is...

This took ... seconds.

2. Calculating The Most Popular Stations and Trip...

The most popular start station is...
The most popular end station is...
The most popular combination of start and end station is...

This took ... seconds.

3. Calculating Trip Duration...

The total travel duration time is...
The mean travel duration time is...

This took ... seconds.

4. Calculating User Stats...

The earliest birth year is ...
The most recent birth year is ...
The most common birth year is ...

This took ... seconds.

After those, the user is presented with the following prompt:

* Would you like to view 5 rows of individual trip data? Enter yes or no
If the answer is yes, then the user sees the first first roes of the dataset for
the selected city, month and day of the week.

Then, the user is asked the following:
* Do you wish to continue?:Enter yes or no.

If the answer is 'yes', the  next 5 rows are displayed. This will continue until the answer is 'no'. In that case, the user will see the following prompt:

* Would you like to restart? Enter yes or no.

If the user answer yes, the process starts again, and the user can chose again city, month and day of the week. And the process continues.

### Credits
Thanks to the mentors at Udacity for helping me with this project. Also stackoverflow and GeeksforGeeks for inspiration and examples.
