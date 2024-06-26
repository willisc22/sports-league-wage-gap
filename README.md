# sports-league-wage-gap
## Table of Contents
* [Motivation](#Motivation)
* [Technologies](#Technologies)
* [Problems & Hurdles](#problems--hurdles)
  * [Getting the Data](#getting-the-Data)
  * [Data Normalization Trouble](#normalizing-the-data)
  * [Hurdles](#Hurdles)
* [Link to Dashboard](#link-to-dashboard)

## Motivation
#### I am a sports fan, through and through. Sure, I have my teams I cheer for just like everyone else, but I will never flip the channel off of a good competition. As a kid, sports raised me in a lot of ways. It was a babysitter when my parents were absent, teammates and their parents were family, coaches were mentors. They have always been a part of my life, and as a now retired college athlete, they serve as entertainment and a way to bring people together to cheer for something. 

#### However, there is another side to sports that is not just wins, losses, and championships. For some people it is their job to perform, and a lot of recent headlines have been bringing to light what the cost of performance is, as well as the monetary dealings of the sports industry as a whole. However, those headlines have also highlighted the just how lopsided athletes across the board are compensated.

####Through this project, I look at several professional sports leagues and work through comparisons among leagues, gender, and international compensations using the Top 100 Active Contracts for each league loaded into an exploratory dashboard. The tool has the goal to aid the user determining what, if any, factors affect or influence the wage gap among these professional athletes. Specifically, team success, generated revenue, and position.

## Technologies
#### Google Sheets and Excel were used for extraction and cleaning, and Python 3 within Jupyter Notebook was used for data exploration. All data with the exception of data pertaining to the MLS was extracted at https://www.spotrac.com/ as CSV files. MLS data was extracted directly from https://mlsplayers.org/resources/salary-guide

#### In order to visualize and compare the cleaned data, Power BI was used to create a dashboard tool.

## Problems & Hurdles
### Getting the Data
#### As mentioned above, data was collected and extracted from two locationsin the following way: 
#### Using the SpotTrac website, I navigated to the page designate for each league and using an import HTML function within Google Sheets, extracted the tables containing the information I felt would provide the greatest support for wage exploration. That information included, contract value, length of the contract, player, position, team, and age of player. The MLS data was extracted in the same manner, just via its repsective websource.
#### After importing, minimal manipulation was needed aside from minor tweaks that were accomplished using Google Sheets and Excel functions.
### Normalizing the Data
#### While working through cleaning, uploading, and organizing my data into Power BI, I came to find that the MLS data was missing information that had been included for all other leagues, but had other data. In this case, the MLS data was missing age at signing, however, the data that was collected was for all MLS active cotnracts, not just the Top 100. When I began comparing the MLS data to other leagues, I found this to actually further highlight stark differences among league compensation.
### Hurdles
#### Intially, all CSVs were loaded into Power BI without any relation. This posed a problem when trying to compare one league to another. I was able to successfully create a new table within Power BI using DAXX functions based on the information I felt necessary to compare for optimal results.
#### While what data that is available is very rich, updated, and well-kept, there is a lot of data that is not publically avaiable. I found that women's sports compensation was not publically available as well as most international professional athlete data. While I believe this dashboard tool is useful for exploration of what is available, I would love to build upon it as more information is made public.

## Link to Dashboard
#### https://app.powerbi.com/view?r=eyJrIjoiNmVjZDI3MmQtMmM1Mi00ZDdhLTliNDItNzZkZWEyOGQ1MzM4IiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9