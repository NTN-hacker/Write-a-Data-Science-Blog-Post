# Writing-a-Data-Scientist-Blog-Post

## Prerequisites

The code is saved in ```.ipynb``` file and can be run with any tool that support this file format. These are libraries that is used in this project:

- pandas
- numpy
- matplotlib
- seaborn
- warnings

### This project aims to answer these questions:

- How age of rider distributed?
- What are percentage of User Type and Member Gender?
- Is there any relationship between duration second and user type?
- Is there any relationship between duration second, gender and user type?
- Is there any relationship between duration second, week day and user type?
- What is top 10 Start and End Station have most rider?

### Results
For the code, please check the notebook ```DS_Udacity_BlogPost.ipynb```.

The findings of this project already published follow the link:

https://viblo.asia/p/do-you-need-to-work-more-effectively-in-the-rental-bike-industry-lets-examine-the-ford-gobike-system-in-san-francisco-in-more-detail-oK9Vyzr54QR

### Data:
This project use data from 201902-fordgobike-tripdata.csv

## Dataset

- The data including information of 183.412 ford gobike trips in San Francisco area with 16 variables (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). But some datas has wrong so it need to be clean them.

## Summary of Findings

- I noticed that the length of journeys is correlated with age, gender, day of the week, and hour. In San Francisco, there is a greater distribution of riders than in Oakland and Berkeley. San Francisco is a popular tourist destination, and as such, it is packed with riders who hire bikes to make getting around the city and beach simpler. In addition, people tend to spend more time bicycling on the weekends because they appear to have employment during the weekdays or because weekend visitors tend to come.

## Key Insights for Presentation

- I just pay attention to the user kinds, age, gender, and location. I began by displaying the start location, selecting the top ten start locations with the greatest number of riders, and advising them to continuously enhance their offerings. The proportion of bike rides for each user type—subscriber and customer—is displayed in the next one. Subcriber users make up 89.2% of the total, while customer users make up 10.8%. The distribution of trip time by user type and days, as well as by gender, is then plotted.

## Reference
- https://seaborn.pydata.org/tutorial/data_structure.html
- https://numpy.org/doc/stable/user/basics.rec.html
- https://matplotlib.org/stable/users/explain/quick_start.html#coding-styles
