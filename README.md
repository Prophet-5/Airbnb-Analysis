# Airbnb Short Term Rental Analysis
## Power BI Dashboard
link:https://app.powerbi.com/view?r=eyJrIjoiNGI4YjU3OTUtNmM3ZS00ODkxLTg4OWEtNThmYzY3YjVmY2MwIiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9
## Table of Contents
- [Power BI Dashboards](#power-bi-dashboards)
- [Motivation](#motivation)
- [Questions](#questions)
- [Cleaning the Data](#cleaning-the-data)
- [Obstacles](#obstacles)
- [Terminology](#terminology)
- [Tools Used](#tools-used)
- [Data Sources](#data-sources)
- [Conclusion](#conclusion)
## Motivation:
Passive income is something that can really help someone have more retirement income. A rental propert is a good way to make passive income and a long-term investment as well. I've been looking into buying a investment property but had no idea how to choose the right areas that are optimal investment potentials. I decided to dig in and collect Airbnb data and other data points that effect housing costs. I then narrowed down the top states that fit into 7 KPI categories:
- Occupancy rate percentages
- Average property tax yearly fees and percentages
- Median home price for that state
- Attractions in that state
- Property value trends as a percentage over 1, 5 , and 10+ years
- Average annual Airbnb Revenue
## Questions:
1. What top 15 states have the highest average occupancy rates?
2. What are the LTR vs. STR net operating incomes for comparison?
3. What is each states average property tax fee and which 15 states have the lowest?
4. What are the median home prices per state?
5. What are the main attractions in states that apply? How many people do they attract yearly?
6. What are some property value trends per state over the years?
7. What is the average annual Airbnb revenue for short-term rentals per state?
## Cleaning the Data
The data sets Ive gathered range from 1991 to 2023 with 1991-2022 being the longest back the property value trend percentages go back to. The occupancy percentages 2023 and 2024 , property tax 2022, tourist attractions 2021, NOI values 2022. I had to take alot of the data into excel and clean to create csv files to then be analyzed in Python. I used a text extracting tool to make tables for analysis within Python.
## Obstacles
I used several different data sets from Zillow, Redfin, Rocket mortgage, Airbitics and Airbnb stat sites. Alot of the data was unavailable in a csv form so I had to scrape the data. The csv files I did get often had a column for each year so I brought them into excel to clean and organize the row structures. Alot of the cleaning was done in excel and Python. Alot of more widespread and deeper analysis data was blocked by a paywall.
## Terminology
LTR = Long-term rental
STR = Short-term rental
NOI = Net operating income (based on 50% reduction of gross from operating costs)
## Tools Used
- Power Point – for the slideshow presentation
- Power Bi – for creating dashboards
- Python/Pandas – for data exploration, cleaning, and data aggregation
- Git – for public display and data housing
## Data Sources
Housing Data - Zillow Research
Redfin | Real Estate & Homes for Sale, Rentals, Mortgages & Agents
15 Best U.S. Cities for Investing in Airbnb | Extra Space Storage
Airbnb vs. Long-Term Rentals: Which Makes the Most Profit? An Analysis of the 50 Largest U.S. Markets - Real Estate ##### Data & Research (renthop.com)
Airbnb Data: Occupancy Rates by Zipcode | Airbtics | Airbnb Analytics
Mapped: The Growth in U.S. House Prices by State (visualcapitalist.com)
Tourist attractions in the United States – Wikipedia
Airbnb Statistics by City in the US 2024 | Hospitable
Property Taxes By State: Highest To Lowest | Rocket Mortgage
## Conclusion
The analysis covers key points of interest associated with short term rental statistics and Airbnb affiliation statistics. I compiled  data samples of "top 15" or "top 10" states from each of the metrics: highest occupancy rates and NOI, lowest property tax, lowest median home prices, highest property value trends and annual STR revenue. After compiling those "top" metrics I counted all the states and how many times they occuureed in those metric lists. For example, TN showed up 6 times in the different KPI metrics such as highest occupancy and lowest property tax. After adding up all the counts each state occurred in the data samples, I made a graph showing the highest and lowest scores. ** Please note that the more attractions a state has, the higher the overall score for that state will be.