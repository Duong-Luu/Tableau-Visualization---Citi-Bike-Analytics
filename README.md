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
	-We can see most of the users are subcriber, and there are higher number of customer usertype in May and June, which can caused by warmer weather and  tourists come to NYC in the summer.
	-We can also see the total Trip count droped by 43% in subcriber usertype in April, this is caused by New York city ordered  the Shelter in Place order by the end of March.
