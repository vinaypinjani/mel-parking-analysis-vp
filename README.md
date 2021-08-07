# mel-parking-analysis-vp
Exploratory analysis has been performed by car parking sensor data provided by the government and a chat bot has been created using Microsoft Azure services that provides those discoveries.

# Data
The project uses data provided by City of Melbourne that contains parking sensor data collected during the first half of 2020 (https://data.melbourne.vic.gov.au/Transport/On-street-Car-Parking-Sensor-Data-2020-Jan-May-/4n3a-s6rn).

# Idea
The idea of the project is to perform exploratory analysis on a sample from the data and answer questions that may generate some information about the parking sensor triggers in  the City of Melbourne. The answers for the questions were used to create a chatbot with Azure services.

# Questions
Questions
1. Which was the most parked street?
2. Most parked street in rush hours?
3. Average parking time for major streets?
4. Areas where most violations occur?
5. Streets with highest average parking time?
6. Which day of the week is busiest?

# Approach
Python is used along with Pandas library to create a dataframe, any non requred columns are removed and necessary conversions are made to the data.

# Implementations
Using Pandas the project uses implementations such as time series analysis, grouping, sorting and basic statistics to generate answers to questions. The chatbot is created with witty responses that makes it very fun to use.
