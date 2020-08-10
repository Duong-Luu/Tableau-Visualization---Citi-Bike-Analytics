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

**Research Questions**:
- How many trips have been recorded total during January 2020 - June 2020?
- By what percentage has ridership grown?
- What are the peak hours in which bikes are used during the weekday? Hourly?
- What are the top and bottom 10 stations in the city for starting a journey?
- What is the gender, age, and customer type breakdown of participants?
