# Twitter WeRateDogs Data Analysis Project

## Dataset
WeRateDogs is a famous twitter page popularly known for humorously rating all kinds of dogs. Dogs are rated on a scale of 1-10, but invariably given rations in excess of the maximum scale, such as 13/10. The account was started in 2015 by college student Matt Nelson, and has received international media attention both for its popularity and for the attention drawn to social media copyright law when it was suspended by Twitter for breaking these aforementioned laws.

## Introduction
This project explores and analyzes WeRateDogs data using webscrapping, wrangling, data visualization and explanation techniques. The project is divided into 3 parts. In the first section, we leveraged on data collection techniques to perform data gathering. WeRateDogs twitter archive data was directly downloaded, requests library was leveraged to download the tweet image prediction and the tweepy library, also used to query additional data via the Twitter API.

In the second section of the data wrangling process dataframes were assessed. Each dataframe was visually and programmatically assessed. Visually Ms.Excel was used to visually assess each DataFrame's full content. Each assessement was documented into two categories quality issues and tidiness issues. 9 data quality issues were documented and 3 data tidy issues respectively. After assessments were made the dataframes were cleaned. Dataframes were cleaned by first outlining the data quality or tidy data issues, defining the solutions on how to tackle respective issues before coding and testing each solution in an hierarchical structure. On completion, the dataframes were merged and stored as a 'CSV' file under the name 'twitter_archive_master.csv'.The libraries used in this project was pandas, numpy, request, os and json.

In the third section, concentration was shifted to analysing the data in it's pure state to generate insights. Data visualization and explanatory techniques were leveraged to generate insights. Reports on how to each section of the wrangling process were written in addition to make the process more elaborative.

## Key Insights
1. Part of the day where @WeRateDogs gain high twitter interactions on their post is from morning to midday (06:00-11:59) on an average

2. Majority of their twitter interactions comes from people using Iphone (i.e. Twitter for iPhone)

3. Puppo's happen to have the highest average ratings
