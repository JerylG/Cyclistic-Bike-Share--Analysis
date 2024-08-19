# Cyclistic Bike Share- Analysis
Google Capstone Project

![Screenshot (32)](https://github.com/user-attachments/assets/03fbb834-3dfc-42e7-860e-31bd3c8f3526)

## Case Study 1: How Does a Bike-Share Navigate Speedy Success?

# Introduction
My capstone project for the Google Data Analytics Certificate Course is the case study below. It entails analyzing historical data for a hypothetical company, Cyclistic, a Chicago bike-sharing company, in order to make marketing campaign recommendations. Although the firm and the scenario are made up, the data for this project was acquired from a Chicago bike share program between June 2021 and May 2022 (a period of 12 months). The information is updated on a regular basis. In this project, I am assuming the role of the junior analyst

# Scenario
Cyclistic is a fictional Chicago-based bike-sharing enterprise. It has a fleet of more than 5,800 bicycles available at over 600 docking stations across the city. Bikes can be leased from one docking station, ridden, and then returned to any of the system’s docking stations. Marketing campaigns have been broad and targeted a cross-section of potential users over the years. Riders who pay for an annual membership are more profitable than casual riders, according to data research. The marketing department is considering developing a campaign to entice casual passengers to become members. The marketing analyst team is curious in the differences between yearly members and casual riders, as well as why casual riders would purchase a membership and how Cyclistic can leverage digital media to persuade casual riders to join. The team wants to look at the Cyclistic historical bike trip data to see whether there are any patterns in how casual and member users use bikes. Further, for data analysis I have used 6 steps that is Ask, Prepare, Process, Analyze, Share, Act to figure out the scenario and come to a conclusion

# 1. Ask

# Business Objective
To enhance revenue by converting casual riders into annual members, through a targeted marketing approach, Business Task for Junior Analyst
How do annual members and casual riders use Cyclistic bikes differently? 
 
# Stakeholders
The stakeholders for this project are Lily Moreno, Director of Marketing at Cyclistic, who is in charge of the company’s marketing campaign.
 
The marketing analytics team of Cyclistic. This group is in charge of gathering, analyzing, and reporting data for marketing efforts. This team’s junior analyst is myself.
 
The Cyclistic management team. This group makes the ultimate decision on the recommended marketing strategy. They are known for their meticulous attention to detail.

# 2. Prepare
 
# Where is the Data located?
The data has been made available by Motivate International Inc., a company employed by the City of Chicago for bike-sharing.
 
# How is the Data organized?
The data is organized in monthly csv files, which keep on updating. The most recent twelve months of data () were used for this project. The files consist of 13 columns containing information related to ride id, rideable type, ride time when it started, ride time when it ended, start station name, end station name, start station ID, end station ID, Start station Latitude, Start station Longitude, End station latitude, end station longitude, members and casuals.

# Credibility of Data
Motivate, Inc., the corporation that manages the City of Chicago’s Cyclistic Bike Share program, collects the data directly.There are some issues with variables though. The data is extensive in that it includes information from all of the rides taken on the system, rather than just a sample. The information is current. It is published on a monthly basis and was current as of May 2022. The data is made accessible to the public by the City of Chicago.
 
# Licensing, privacy, security, and accessibility
All identifying information has been removed from this data, making it anonymous. This protects privacy but also restricts the scope of the investigation. There is insufficient data to tell whether casual riders are repeat riders or if casual riders are Chicago residents. The data has been made available by Motivate International Inc. under this license(https://ride.divvybikes.com/data-license-agreement (https://ride.divvybikes.com/data-license-agreement))
 
# Data Integrity and Ability to be used to answer Business Questions
The type of rider is recorded in one of the fields in the data; casual riders pay for individual or daily rides, whereas member riders pay for an annual subscription. This data is necessary in order to identify differences in how the two groups use the bike-share program.

# Problems in the data
There are some problems with the data. Missing records and duplicate records in the data set as well as having the trip duration <=0

# 3. Process

# Tools used
For this project I choose to use RStudio Desktop to clean, analyze the data and to create the visualizations. The data set was too large to be processed in spreadsheets and RStudio Cloud.

# Data Cleaning
Data was examined to gain a general understanding of field content, data formats, and data integrity. Checking column names throughout the 12 original files and looking for missing values, trailing white spaces, duplicate records, and other data abnormalities were all part of the data assessment. I first installed all the required libraries and then loaded them. After this, I set up the working directory and uploaded the csv files. The libraries that were loaded were tidyverse, janitor, lubridate, dplyr, readr, skimr, ggplot2 and gridExtra. The cleaning is done in the Analysis folder in R markdown.

# 4. Analysis

I have done the Analysis in markdown in R which can be found in the Analysis folder

# 5. Share

Data analysis was followed by clear visualizations to effectively communicate insights to stakeholders. For a deeper dive, please refer to the visualizations shared in the dedicated folder.

# 6. Act

# Recommendations
Based on an analysis of the data, the following recommendations can be made to the Cyclistic stakeholders.
1. The marketing campaign should be targeted at the popular start and end stations for casual riders by providing discounts and certain benefits in order for them to enroll for membership.

2. To encourage casual users to enroll, weekend specials should be introduced which would cut down the cost of memberships to some extent as weekends are the busiest for casuals and more importantly the discounts should be applied more during the busiest time of the month for casuals that is October.

3. Introduce a “reservation” system allowing members to schedule a bike ahead of time during busy periods (e.g. weekends or October), effectively being able to skip the line during high-demand times.











