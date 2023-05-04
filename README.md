# Tableau Challenge
![Alt text](/Images/citi-bike-station-bikes.jpg)

In this challenge, I compared NYC Citibike data from June 2013 to June 2015. I first cleaned the data in Pandas.

I started this challenge wanting to compare June 2013 to June 2022. Unfortunately, the data collected was quite different and time did not allow cleaning it in a useful way. I decided to use another year when the data collected was more similar, so I chose 2015.

The June 2022 data seems to be quite 'dirty.' When I first started comparing it to 2013 data, the number of total minutes was so much lower than that of 2013 and 2015. I started looking into outliers, but realized that time was limiting me to dig into it.

My next steps would be to sort out the outliers from 2013 and 2015 to see if the average minutes and total minutes were artificially padded because of people who rented bikes over several days instead of for a shorter period per one day. There was an outlier in the June 2022 data where someone had the bike for an entire month.

I was surprised to see that biking appeared to be less popular in 2015 than in 2013. I looked at weather data to see if that could have been the reason, but both years had similar weather. My hypothesis is that there are a number of outliers in the data.
