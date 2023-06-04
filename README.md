# **Google-Data-Analytics-Capstone-Project** #

### *Introduction:* ###

In this case study, I will perform many real-world tasks of a junior data analyst at a fictional company, Cyclistic. In order to answer the key business questions, And from data help to unswer business questions. I will follow the steps of the data analysis process: Ask, Prepare, Process, Analyze, Share, and Act.

---
Data Source : [divvy_tripdata](https://divvy-tripdata.s3.amazonaws.com/index.html)
---
## *Details* ##

### Cyclistic ###
A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.

Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno (the director of marketing and my manager) believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.

Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends.

---
### Scenario: ###

I am assuming to be a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, my team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve our recommendations, so they must be backed up with compelling data insights and professional data visualizations.

---
## Ask ##
### Business Task: ###
Devise marketing strategies to convert casual riders to members.

### Analysis Questions ###
Three questions will guide the future marketing program:

1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?
Moreno has assigned me the first question to answer: How do annual members and casual riders use Cyclistic bikes differently?

## Prepare ##
### **Data Source** ###
I will use Cyclistic’s historical trip data to analyze and identify trends from Jan 2022 to Dec 2022 which can be downloaded from divvy_tripdata. The data has been made available by Motivate International Inc. under this license.

This is public data that can be used to explore how different customer types are using Cyclistic bikes. But note that data-privacy issues prohibit from using riders’ personally identifiable information. This means that we won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes.

### **Data Organization** ###
There are 12 files with naming convention of YYYYMM-divvy-tripdata and each file includes information for one month, such as the ride id, bike type, start time, end time, start station, end station, start location, end location, and whether the rider is a member or not. The corresponding column names are ride_id, rideable_type, started_at, ended_at, start_station_name, start_station_id, end_station_name, end_station_id, start_lat, start_lng, end_lat, end_lng and member_casual.

---
### Process ###
Excel is used to combine the various datasets into one dataset and clean it.

### Combining the Data & Cleaning Data ###
First I delete the emty and missing rows, And delete the Dubplicate Values.
Then I merge it in Excel. Using Append option.

---
## Analyze and Share ##

Data Visualization: [Tableau]
The data is stored appropriately and is now prepared for analysis. I queried multiple relevant tables for the analysis and visualized them in Tableau.
The analysis question is: How do annual members and casual riders use Cyclistic bikes differently?

![the result](https://1drv.ms/i/s!AoNyQ05J_zUajBJYRKrXKqPDYptp?e=4rkygU)


***Summery***
|Casual|Member|
|---|---|
|Caual Rider's Used their bikes more in throughout the day.|Prefer riding bikes on week days during|
|Travel longer * 2 but less frequently than members.|Travel more frequently but shorter rides|
|Casual rider Start and end their journeys near the parks, museums, along the coast.|Start and end their trips close to universities, residential and commercial areas.|

---
## Act ##
After identifying the differences between casual and member riders, marketing strategies to target casual riders can be developed to persuade them to become members.
Recommendations:

1. Marketing campaigns might be conducted in spring and summer at tourist/recreational locations popular among casual riders.
2. Casual riders are most active on weekends and during the summer and spring, thus they may be offered seasonal or weekend-only memberships.
3. Casual riders use their bikes for longer durations than members. Offering discounts for longer rides may increse casual riders and members to ride for longer periods of time.
