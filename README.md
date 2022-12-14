# Ford GoBike System Data
## by Kola Ademola


## Ford GoBike System Data

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.  
After loading the dataset I took the following steps in my wrangling/cleaning process:
* I started by assessing the data visually & programmatically.
* I created a copy of the dataset before cleaning.
* I noticed issues with data types where multiple columns were formatted as the wrong data types which I re-formatted properly.
* I also spotted columns with missing values which I filled appropriately and the ones I couldnt fill I dropped them.
* I dropped the columns that were not neccesary for my analysis.
* I also did feature engineering to add some columns/features that would be helpful fot my analysis.
* After wrangling/cleaning of the data I moved on to the following data explorarion:
    * Univariate Exploration.
    * Bivariate Exploration.
    * Multivariate Exploration.  
The above summarises my data wrangling and analytics process for this project.

## Summary of Findings

After using Univariate, Bivariate & Multivariate exploration to check my variables of interest and this is the summary of my findings:
* I discovered that younger people between **18-50** years old take more trips and even subscribe more.
* Majority of the people that take trips are just Customers.
* Majority of trips were taken **5PM** & **8AM** but then I also noticed that the longest trips were taken **3AM** & **2AM**.
* Male takes more trips but they appear to be for shorter distance/duration.
* **Thursday** & **Tuesday** came out as the days that most trips were taken, I thought it would be on weekends though.
* Number of trips start declining after the 3rd week of the month.

## Key Insights for Presentation

For the presentaion I'll like to focus on how age affects the number of trips and even the number of people that subscribe to the Bike share program. I'll start by introducing the age variable and then show how it is distributed accross the dataset.

After which I introduce how the diffrent age groups come out on:
    * The number of trips taken using a simple bar chart
    * The proportion of Subscribers to Customers using a simple pie chart
    * The number of subscribers compared to customers for each age group using a simple clustered bar chart for easy comparison.
    * The trend of trips taken over the month using a line plot.