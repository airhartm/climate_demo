# climate_demo
Application of Python and Tableau to global temperature trends

This demonstration project collects global temperature data since the year 1995 from the University of Dayton. The data consists of average daily temperature reported by cities around the world. The data comprises 2.9 million lines of data in a .csv file.

The data is retrieved and cleaned via Python, then visualized in Python, Tableau Public, and Microsoft Excel.

What is the goal of your data analysis project? 
Track 20-year change in average temp in 5 U.S., 5 international cities for potential A/C sales.

US Cities
Denver, Colorado
Grand Junction, Colorado
Pueblo, Colorado
Salt Lake City, Utah
San Angelo, Texas

International Cities
Belgrade, Serbia
Bishkek, Kyrgyzstan
Madrid, Spain
Milan, Italy
Zagreb, Croatia

Context and use cases:

-- We hypothesize an air conditioning company that is looking to expand its reach to the cities that are feeling the effects of climate change. Our primary goal is to track 20-year changes and predict climate trends in 10 cities in order to ramp up production or invest in these cities. Our presentation will be to investors who will want to see visualizations of our findings.
-- Create visualizations in Tableau.
-- Create easily digestible presentation to investors on why we want to expand our business.

Data sources used for the analysis: 

The dataset comprises the daily average temperature for global cities between 1995 and 2019. The data was provided by the University of Dayton via Kaggle:
https://www.kaggle.com/datasets/sudalairajkumar/daily-temperature-of-major-cities

The data consists of 2.9 million daily temperature entries. The data contains the following gaps:

-- A null state or province for cities in most nations other than the United States.
-- Just under 80000 entries report a temperature of -99 which is the dataset’s code for unavailable temperatures. Some of these entries also reported a year of “201.”
-- A few entries had a value of zero for the day.

What tools and techniques will you use to analyze the data? 

Python
Count, separate, and remove rows with temperatures that are null or not available, or with day numbers of zero
Calculate rolling mean and median averages of temperature changes
Calculate average temperatures in the five-year periods that bookend the data, then calculate the difference 
Calculate and filter the cities with the greatest changes, in the U.S. and globally 

Tableau
City by city, show patterns in city’s data. Predict temperatures in 2025 if possible.
Temperature overview for all cities

Intended audience for the project 
-- Investors

What potential challenges or limitations do you anticipate in your project? For example, are there any data quality issues you'll need to address?
-- Minimal null data
-- Lack of info on local economy, affordability of A/C, local culture
-- Some cities in initial priority list may be obviously inappropriate (e.g. war zones, trade embargoes, inaccessibility) 

