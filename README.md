# Motor-Theft-Analysis
## By Ezerioha Ifeanyi Emmanuel

## Dataset
https://maven-datasets.s3.amazonaws.com/Motor+Vehicle+Thefts/Motor+Vehicle+Thefts+CSV.zip
Stolen vehicle data from the New Zealand police department's vehicle of interest database containing 6 months of data. Each record represents a single stolen vehicle, with data on vehicle type, make, year, color, date stolen and region stolen.

### This analysis seeks to answer the following questions:
- What day of the week are vehicles most often and least often stolen?
- What types of vehicles are most often and least often stolen? Does this vary by region?
- What is the average age of the vehicles that are stolen? Does this vary based on the vehicle type?
- Which regions have the most and least number of stolen vehicles? What are the characteristics of the regions?

## Data Cleaning Process:
A lot of data manipulation was done to clean the dataset and prepare it for data analysis.

During the data cleaning process, vital columns that gives information about a car was missing, and therefore the need to filter those columns out. Upon filtering out the rows out, we have 4527 rows with no missing value across its column.
Date columns was splitted to have years, day and month for the purpose of analysis.
Lot of values were replace to better understand the visualization such as: changing 1 to January, 12 to December; 0 to Sunday, 1 to Monday, ..., 6 to Saturday after extracting the day of week from the date_stolen column



## Data Insights
- The total population is Five Million
- The total number of stolen vehicle was 4527
- Stationwagon happen to be the Vehicle type often stolen
- Special Purpose Vehicle is the least stolen vehicle car
- Vehicle with Model Year 2006 happens to be stolen the most
- Off all regions, Auckland happens to be the most populated
- Vehicles were mostly stolen on Monday, and least stolen on Saturday
- Auckland happens to be the region suffering the most from vehicle theft while Southland is the region with the least amount of stolen vehicles
