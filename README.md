# Tableau Visualization - Citi Bike Analytics
**Tableau Public Workbook**: [Citi Bike NYC - 2020 Q1 & Q2 - Summary Report](https://public.tableau.com/profile/duong.luu8235#!/vizhome/CityBikeAnalysisReport2020Q1Q2/CitiBike2020Q1Q2AnalysisReport?publish=yes)

**Data Source**: [Citi Bike System Data](https://www.citibikenyc.com/system-data)


**Objective**: Aggregate the data in NYC Citi Bike Trip History Logs and design visualizations for each discovered phenomena. The Timespan chosen is January 2020 - June 2020.
**ETL**: 
- Extracted data from Citi Bike System Data for January 2020 - June 2020
- Transformed data in Jupyter Notebook:
	- Appended each csv file to a combined dataset
	- Replaced Gender variables of 0, 1, 2 to Unknown, Male, and Female
	- Created and saved this dataset into a csv file
- Loaded dataset into a Tableau Workbook

## Analysis

- **Overall**
	- Total Number of Trips: 7,508,808
	- Average Trip Distance(miles): 2.34
	- Average Trip Duration(minutes): 21.6
	- Top User by Age Group: Millennials (24-39 years)
	- Top User by Gender: Men
	- Top User by Customer Type: Subscriber

- **Station Popularity**
	- We can see the popular stations are in Midtown Manhattan, which has many businesses, tourist attractions, and corporate offices.
	- There are many popular stations in both Manhattan and Broklyn near the Williamsburg Bridge, and also in the west side bike path along the Hudson River.
	
- **Ridership Growth**
	- We can see most of the users are subcriber, and there are higher number of customer usertype in May and June, which can caused by warmer weather and  tourists come to NYC in the summer.
	- We can also see the total Trip count droped by 43% in subcriber usertype in April, this is caused by New York city ordered  the Shelter in Place order by the end of March.

- **User Demographics**
	- The majority of the riders are Male Millennials, which account for 77% of all subscriber trips.
	
- **Bike Usage: Ridership Peak Hours (Daily and Hourly)**
	- Bike Usage looked into when is the highest Citi Bike usage by weekday and by hour
	- We can see the peak hour  at 8am in Q1 but not in Q2, which due to New York city ordered  the Shelter in Place order by the end of March. People can work from home instead traveling to offices, but people still doing excercise/errands in the evening.
	- Both Q1 and Q2 have peak hour at 5pm as people presumably head home from their Midtown offices. 
	- From 1am to 3am, people tend to spend on average 35 minutes cycling and socializing, which is special and unique to New York City. There are many Night Bike Ride Tour in the Central Park and thorugh out New York City.

![](https://github.com/Duong-Luu/Tableau-Visualization---Citi-Bike-Analytics/blob/master/Citi%20Bike%20NYC%20-%202020%20Q1%20%26%20Q2%20-%20Summary%20Report.gif)
