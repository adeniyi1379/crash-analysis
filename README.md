# Plane crash-analysis
This is my capstone project after the NG30DaysOfLearning
# Data source
The data is available in the github repository at [here](https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/blob/main/Airline%20Project/Airplane_Crashes_and_Fatalities_Since_1908.csv)

# Problem Statement
The purpsose of this project is to anwer the following questions
1. How many People have lost thier life due to plan crashes during the period?
2. Which country and location as the highest number of crashes?
3. Is weather condition a major cause of plane crahes?
4  And lastly what trend is between people on board, fatalities and survivors

# Data Cleaning/Transformation
The data was first loaded to microsoft excel for inspection so i could have clear understanding of what i want to work with the after
I load the data to Power Query in powerBi to do the following cleaning
1. Change the Date column data type from text to date
2. Extract Year and Month from date column since i know i will be doing some analysis based on year and month
3. Replace empyt value in location and summary column to known
4. Replace empty value in aboard and fatalities column with 0
5. Subtract fatalities from aboard to get my survivor column
6. Check and change every column to a suitable data type

# Data Analysis and Visualzation
1. The image below show that 5268 crashes occur during this period and has taken the life of 144,551 people, that is 72.97 fatality rate.
![top](https://github.com/adeniyi1379/crash-analysis/blob/main/image/top.png)

2. Russia has the highest number of crashes because they own the aeroflot airline which is the operator with most crashes, the reason why aeroflot
as more crashes compare to other operaro is not part of this analysis.
![img](https://github.com/adeniyi1379/crash-analysis/blob/main/image/location.png)

3. Tenerife is location with most fatalities because of the incident that happen in 1997 whern two plane collide.
![img](https://github.com/adeniyi1379/crash-analysis/blob/main/image/location%20by%20fatalities.png)
4. With most crashes during the autumn and winter season that comes with rain, wind, thunder and heavy rainfall, this is a clear indication that weather is a major causes of plan crashes.
![img4](https://github.com/adeniyi1379/crash-analysis/blob/main/image/season.png)

# Recommendation
- Weather forecast information should be checked and used by airlines before flying mostly during the autumn and winter season.


## The full image of each section is found below
![dashboard](https://user-images.githubusercontent.com/46291970/179718513-14a16a2b-6e6a-4ead-b45c-135211e07d38.png)
![summary](https://user-images.githubusercontent.com/46291970/179718600-8aadb7db-3b80-4d3c-8936-c6631bd10891.png)
![fatalities analysis](https://user-images.githubusercontent.com/46291970/179718612-cacd7afa-670d-40f0-ae2a-42e993508633.png)
